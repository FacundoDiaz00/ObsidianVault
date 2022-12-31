# Parcial 2021:

## Pregunta 1:

Qué tipo decircuito es la CPU, y que acciones realiza. Descriva los estilos de diseño de CPU.

La *cpu* es principalmente un circuito combinatorio, esto se debe a que el msimo contiene a la *alu* que implementa funciones booleanas que permiten el funcionamiento del mismo.
A su vez es posible (y común) que la cpu implemente circuitos secuenciales, como es el caso del registro de memoria.
La cpu se encarga de proveer funciones booleanas que serviran como instrucciones de bajo nivel que la computadora podrá realizar.
Los estilos de diseño de Cpu vistos en el curso son RISC y CISC, el primero de ellos intenta minimizar la cantidad y complejidad de las funciones que provee la alu, con la intencion de permitir que las mismas se resuelvan de forma mas eficiente. La segunda implementa un gran numero de funciones complejas, lo cual brinda facilidades al programadaor de bajo nivel.
(preguntaba otra cosa, leí mal).


Explique qué tipo de circuito es la Unidad de Control de una CPU y qué acciones  
realiza. Describa los estilos de diseño de Unidad de Control vistos en el curso.

Solución  
Respuesta Pregunta 1  
La unidad de control es una máquina secuencial. Su acción es realizar el ciclo de  
instrucción, un conjunto de acciones ordenado y secuencial para lograr ejecutar cada  
instrucción, aplicando una operación determinada sobre los operandos  
correspondientes y almacenando el resultado en un lugar indicado.  
Las opciones vistas en el curso para el diseño de la unidad de control son el control  
cableado o la microprogramación.  
En el caso del control cableado, la UC se diseña como un circuito secuencial  
utilizando, por ejemplo, la metodología de Máquinas de Estado. En el caso de la  
microprogramación, la UC se construye en base a una máquina secuencial más  
simple que ejecuta los microprogramas que contienen la secuencia de valores de las  
señales internas de control de la CPU para lograr la ejecución de las instrucciones.

## Pregunta 3

¿Cuántas ROMs de 2Kx6 se precisan para construir una ROM de 1Kx12 ?  
Dibuje el circuito correspondiente

Si bien ambas rams tienen la misma capacidad, en este caso 12k bits. Son necesarias dos ROMs para lograr los 12 bits de ouput deseados.

![[ArquiParcial2021Ej3.excalidraw]]

## Pregunta 4
Considere dos procesadores diferentes (CPU1 y CPU2), los cuales implementan una  
misma caracterización de una arquitectura Von Neumann.  
Indique si las siguientes afirmaciones son verdaderas o falsas. Justifique su respuesta.  
- Para todo programa en alto nivel que se compila y ensambla para la CPU1, el  
mismo código binario también puede ser ejecutado en la CPU2.  
- Para todo programa en alto nivel, que se compila y ensambla para la CPU1 y  
además se compila y ensambla para la CPU2, la ejecución del programa en ambas  
CPUs durará la misma cantidad de ciclos de reloj.

$1.$ Debido a que ambas cuentan con las mismas operaciones basicas a a nivel de cpu, el mismo codigo de assembly podrá ejecutar sus instrucciones independiente de cual de dichas cpus sea utilizada.

$2.$ No necesariamente, defectos en el silicio y cosas asi capaz nose.

Respuesta Pregunta 4  
1) Verdadero. La caracterización de la arquitectura Von Neumann está compuesta  
por los distintos elementos señalados en el curso: set de instrucciones, formato de

instrucción, set de registros, modos de direccionamiento, manejo de entrada/salida e  
interrupciones.  
En la literatura se la describe como la interfaz entre el hardware y el software, es  
decir, brinda la información necesaria para escribir programas en lenguaje de  
máquina.  
Decir que dos CPUs poseen una misma caracterización de la arquitectura Von  
Neumann implica que pueden ejecutar todos los programas que cumplan la  
especificación, sin importar en cuál se ellas se haya compilado el mismo.  
2) Falso. Si bien ambas CPUs pueden ejecutar el programa (por la parte anterior  
se desprende que el código binario es el mismo), no se especifica cómo lo hacen. Por  
ejemplo una de las CPUs podría incluir o no un pipeline en su organización, lo cual  
va a provocar que los programas ejecuten en una menor cantidad de ciclos de reloj.  
Otros ejemplos podrían ser que implementaran ciclos de instrucción distintos, o que  
una CPU tuviera su Unidad de Control diseñada por control cableado y la otra por  
microprograma.

## Pregunta 5.
![[Pasted image 20220920213220.png]]

Se observa que la tabla de verdad de la funcion implementada por el mux es la siguiente:
| a   | b   | Y   |
| --- | --- | --- |
| 0   | 0   | 1   |
| 0   | 1   | 0   |
| 1   | 0   | 0   |
| 1   | 1   | 1   |
La misma corresponde a la negacion de $XOR$, tambien llamado $XNOR$.

![[ArquiParcial2021Ej5.excalidraw]]

(bien).

