# CPU
#### From [[Arquitetctura en Comp/Arqui]], [[ArqVanNeuman]]

## Organizacion de la CPU

### ALU
Contiene los circuitos combinatorios que permiten realizar operaciones.
Implementa operaciones como :
- Suma/Resta (normalmente mediante complemento a 2, ya que mantiene las operaciones)
- Operaciones logicas: $AND,OR,NOT,XOR$
- Pueden, opcionalmente implementar otras operaciones como multiplicacion o division (es posible que se implementen en la ALU mediante circuitos que no sean necesariamente combinatorios, se implementa combinatoriamente el *paso multiplicativo*)}

### Banco de registros
Contiene registrios de tres categorias desde el punto de vista de su función en repación con los programas y el funcionamiento interno de la CPU.

- **Totalmente visibles**: estos son los ya mencionados registros de uso general ó  personalizados que **contienen operandos o direcciones** para su utilización en las  instrucciones. El programador de “bajo nivel” los manipula directamente en los  programas.
- **Parcialmente visibles**: son registros que tienen **funciones especiales** pero  
participan de algún modo indirecto en las instrucciones. 
El programador los  manipula indirectamente en determinadas instrucciones específicas. 
Ejemplos  de este tipo de registros son el *IP* (Instruction Pointer), también denominado PC  (Program Counter) que contiene la dirección de la próxima instrucción a  ejecutarse (en algunas arquitecturas almacena la dirección de la que se está   ejecutando en este momento), el SP (Stack Pointer) que contiene el puntero al   primer lugar de la pila en las arquitecturas “de stack” y el PS (Processor Status)  también denominado registro de FLAGS (en el caso de Intel) que contiene el   estado del procesador incluyendo el valor que tomaron los bits de condición   (Negative, Zero, Carry, Overflow) en función del resultado de la última operación  realizada por la ALU.
- **Internos**: Son regisrtos utilizados para poder ejecutar las operaciones, Almacenan **constantes**, el **estado de la CU**, la **instruccion en ejecucion**, **reusltados intermeidos** de calculos, etc. **No visibles al programador**.

### Unidad de control.
**Máquina secuencial** que realiza el “**ciclo  de instrucción**”: conjunto de acciones ordenado y secuencial que interconectan  adecuadamente los distintos elementos en el tiempo, para lograr el objetivo de ejecutar la  instrucción realizando la operación indicada sobre los operandos correspondientes y  almacenando el resultado en el lugar indicado. Esta máquina secuencial **funciona  sincronizada por un reloj**, el cual también es utilizado para sincronizar todas las actividades   de los otros elementos del sistema (memoria y entrada/salida).
Segun la instruccion la unidad de control envia las señales al resto de componentes de la forma necesaria para que se lleve a cabo la operacion deseada.
Por ejemplo al realizar una multiplicacion, la uc estaria encargada de realizar suscesivas sumas, podra pasar por distintos estados dependiendo si, por ejempo una flag indica o no 0, etc.++
## Ciclo de instruccion:
Un ciclo de instrucción típico tiene 5 pasos característicos:  
- **Fetch**: este paso consiste en **leer la próxima instrucción** a ejecutarse desde la  memoria.  
- **Decode**: en este paso se analiza el código binario de la instrucción para **determinar qué se debe realizar** (cuál operación, con qué operandos y donde  guardar el resultado)  
- **Read**: en este paso se **accede a memoria** para traer los operandos  
- **Execute:** es la ejecución de la operación por parte de la ALU sobre los  
operandos  
- **Write**: en el último paso se **escribe el resultado en el destino indicado** en la  
instrucción.

(No todas las operaciones requieren de todos los pasos.)

Ejemplo, CPU MIC-1.
![[Pasted image 20220921151824.png]]

## Lógica cableada vs Lógica microprogramada.

### Logica cableada:
El diseño de la CU en base a la filosofía de “**lógica cableada**” se hace como  
cualquier **circuito secuencial**: en base a un diagrama de estados traduciéndola a una máquina de Mealy (por ej.). Para el  ejemplo anterior deberíamos tomar como salidas todas las señales de control necesarias y   como entradas los bits del código binario de las instrucciones.
En este caso el resultado es óptimo desde el punto de vista de la velocidad de los  circuitos, pero tiene **poca flexibilidad** ya que cualquier cambio en el diseño del set de instrucciones de la CPU genera la necesidad de cambiar todo el circuito lógico que lo implementa.

### Logica microprogramada:
La CU **se contruye a partir de un autómata** que ejecute el ciclo de instruccion siguiendo una secuencia de "**microinstrucciones**" que contienen los valores de las señales apropiados para esa istrucción particular.

Para cada  instrucción a nivel de la CPU existirá un “**microprograma**”, consistente en una secuencia  lógica de microinstrucciones que establecerán el orden de los eventos necesarios para  lograr la ejecución de la instrucción en la CPU, incluyendo todas las “bifurcaciones”.

En este caso hay una **penalización** en la  velocidad de proceso porque el microprograma se almacena en una ROM interna de la  CPU y cada microinstrucción debe ser leída de ella, pero simplifica enormemente la tarea  
de modificar el set de instrucciones.


### Microinstrucciones.
![[Pasted image 20220922005604.png]]
(esto se refiere a los inputs que requiere la uc para conocer el estado de la cpu, esto implica que deberan formar parte de la codificacion de la microinstruccion)
![[Pasted image 20220922005950.png]]
Los 8 bits de ADDR corresponden a la direccion de la proxima microinstruccion si hay un salto. Los dos bits de COND describen si habrá un salto o no dependiendo del estado de las banderas.
Esta arquitectura permite un maximo de 256 microinstrucciones, correspondientes a las que son posibles distinguir mediante el ADDR.
![[Pasted image 20220922010048.png]]
![[Pasted image 20220922010744.png]]
### Microprogramacion vertical o horizontal.
![[Pasted image 20220922011014.png]]
(se debe indicar UNO de los registros para conectar al bus A, lo mismo para cada BUS, esta codificacion no permite que se seleccionen varios registros simultaneamente)
![[Pasted image 20220922011053.png]]
![[Pasted image 20220922011147.png]]

    In the Horizontal micro-programmed control unit, the control signals are represented in the decoded binary format, i.e., 1 bit/CS. Here ‘n’ control signals require n bit encoding. On the other hand. 
    In a Vertical micro-programmed control unit, the control signals are represented in the encoded binary format. Here ‘n’ control signals require log2n bit encoding. 