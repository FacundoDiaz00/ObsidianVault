[[ArqVanNeuman]]
[[notas pipeline.pdf]]

La técnica de pipeline apunta a mejorar el rendimiento sin necesidad de aumentar la frecuencia de trabajo, utilizando los mismos principios que Henry Ford introdujo en las formas de producción industrial a principios del siglo XX: la producción en cadena ó cadena (línea) de montaje.

![[Pasted image 20221116002937.png]]

suponiendo que el Fetch se haga en un solo ciclo de reloj (lo que no es cierto si se tratara de una arquitectura CISC que tiene largo variable de instrucción), hay algunos elementos que pueden afectar el funcionamiento óptimo del pipeline. El más evidente es que existe el mismo problema con las instrucciones de salto que vimos para el caso anterior. Ya sea que identifiquemos el salto en la etapa de Decode (si es incondicional) ó en la etapa de Execute (si es condicional), las instrucciones siguientes que ya se hayan leído se deberán descartar.

#### Pipeline simple. 
Implementado en 8086, divide el ciclo de instrucción en dos etapas: Fetch y Execute.
Pueden darse situaciones de espera en alguna de las etapas debido a diferencias en el largo de instruccion o necesidad de multiples lecturas.
#### Pipeline de 5 etapas
(Ver imagen)

## Hazards
+ *Hazards Estructurales*: hay un conflicto de hardware entre dos o más etapas del  
pipeline para alguna combinación de instrucciones.  
+ *Hazards de Datos:* existen dependencias de datos entre instrucciones. Por ejemplo la ejecución de una instrucción depende del resultado de otra previa, que aún está en el pipeline.  
+ *Hazards de Control*: causados por instrucciones de salto u otras modificaciones del registro IP (Instruction Pointer ó PC = Program Counter).

### Hazards Estructurales:
Un ejemplo de este tipo de hazard se da en el hardware de acceso a memoria entre  
la etapa de fetch y alguna que lea ó escriba en memoria:

![[Pasted image 20221116003837.png]]
Caso azul: Dos intentos simultaneos de uso del bus de comunicación. Se soluciona utilizando *arq Harvard*, en la cual tenemos *memorias separadas para datos e instrucciones*.

Caso Rojo, *Choque de Execute y Fetch*, Dado que Fetch necesita *calcular la doreccion próxima de instrucción* ambas instrucciones estan intentando usar la ALU. Se puede solucionar con un *sumador independiente* para el caluclo de dir de prox instruccion.

Una solucion general al problema de falta de recurso de hardware es esperar. Una forma de esperar es agregarm artificialmente, operaciojnes del tipo "NOP"

### Hazards de Datos.

Datos en común entre instrucciones que están en el pipline. (instruccione siguiente utiliza un resultado aún no calculado como operando o altera operando antes de que sea leído)

Hay 3 tipos de Hazards de Datos:

#### RAW (Read After Write)
Una instruccion intenta obtener un operando que est asiendo calculado, que aun esta en el pipeline y no ha llegado a la etapa write.

#### WAR (Write after Read)
Instruccion escribe un registro que actua como operando de una instruccion anterior antes de que esta pueda leerlo

#### WAW (Write after Write)
Instruccion anterior escribe un registro que tambien actua como resultado de una instruccion posterior *despues* que esta. (la instruccion mas tardia escribe antes por lo que es sobre escrita) (no es posible en los pipelines vistos)


Para el caso del RAW las formas de resolver el problema pueden ser:  
+ esperar (introducir una burbuja en el pipeline)  
+ recurrir a técnicas avanzadas como la ejecución fuera de orden (out of order  execution)
+ hacer *register forwarding*. Esta técnica consiste en *propagar hacia las etapas tempranas del pipeline los resultados apenas estén disponibles*, sin necesidad de  esperar a que culmine la etapa de Write. En este caso la etapa de Read podrá  leer el operando desde el registro indicado ó desde la salida de la ALU  directamente, en función de la lógica de control que implemente esta  funcionalidad.

### Hazards de Control.

#### Prefetch del destino.
Realizar simultaneamento el fetch de la proxima instruccion en memoria y de la instruccion apuntada por la direccion destino del salto. Se efectiviza la instruccion que corresponde a la secuencia logica, la otra se descarta.

#### Multiples flujos.
Expande el anterior, duplica las etapas del pipeline que están ubucadas hasta la que decide el salto. Por lo que se puede avanzar en la ejecucion de ambos flujos de instrucciones. Al momento de tomar el salto no hay ninguna penalización ya que no es necesario "vaciar" el pipeline.

#### Salto demorado
Se ejecuta la instruccion que está luego del salto (delayed slot). ES RESPONSABILIDAD DEL COMPILADOR (o programador) UTILIZAR ALLI UNA INSTRUCCION UTIL, nunca se colocan dos saltos seguidos (prodice excepcion)
Si no hay forma de aprovechar el delayed slot se coloca un NOT

#### Prediccion de salto.
La técnica consiste en determinar, en base a un cierto algoritmo o criterio, si el salto se va a tomar o no

![[Pasted image 20221116010158.png]]

### Ejecucion fuera de orden.
Metdoo para solucionar hazards.
Para lograr esto los procesadores que utilizan esta técnica manejan un conjunto de instrucciones que ya fueron leídas desde la memoria hacia una especie de “estacionamiento, y las van catalogando como “prontas para ejecutar” o no en función que sus dependencias de datos y control hayan sido satisfechas. Las instrucciones “prontas para ejecutar” avanzan en el pipeline a la etapa de ejecución y a medida que se van generando nuevos resultados, se van actualizando los estados de las instrucciones que aún esperan.