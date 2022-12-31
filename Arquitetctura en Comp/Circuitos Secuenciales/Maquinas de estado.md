# Maquinas de estado.
#### From [[Circuitos Secuenciales]]


## Estado.
Se defuine una relacxion de equivalencia entre dos secuencias de valores de netradas de un circuito secuencial dado.
Dos secuencias de entrada son *equivalentes* si:
+ Counciden a partir de cierto punto 
+ a partir de dicho punto la salida del circuito es la misma para ambas secuencias.

*A cada clase de equivalencia le corresponde un $ESTADO$ del circuito secuencial.*

Solo nos interesaran los casos con finitas clases de equivalencia, ya que de otra forma no es posible construir un circuito secuencial que tiviera ese comportamiento (demostracion en asignaturas de Ciencia de la Computacion)


## Automatas finitos Deterministas.

Los AFD son un modelo matemático de un sistema con entradas y salidas discretas.

Formalmente, los automatas finitos o maquinas de estado, son cuaternas:
	$M = (E,\Sigma,\delta, e_0)$ donde $E$ es un conjunto finito de estados, $e_{0}\in E$ es el estado inicial y $\Sigma$ es el alfabeto de entrada. $\delta: E\times\Sigma \rightarrow E$ es la función de transición.

## Maquina de Mealy

Una maquina de Mealy es una tupla $M = (E,\Sigma,\Delta,\delta,\lambda, e_0)$ donde $\Delta$ es el alfabeto de salida y  $\lambda:E\times\Sigma\rightarrow\delta$ es la funcion de salida.

## Implementacion.
Las maquinas de estado pueden ser implementadas mediante el uso de circuitos secuenciales utilizando[[Flipity-flopityflop]].

Ej:
![[Pasted image 20220912155324.png]]


La tabla $\delta$ nos da info de las trancisiones.
La tabla $\lambda$ nos da info de las salidas.

## Maquina de Moore.

Una maquina de Moore es una tupla $M = (E,\Sigma,\Delta,\delta,\lambda, e_0)$ En este caso $\lambda:e\rightarrow\Delta$ por lo que: *La salida solo depende del estado en el que se encuentra la maquina, no del estado y el input como el caso anterior*

## Ejemplo: Contador binario mod 4

![[Pasted image 20220912175618.png]]
Se dibuja la maquina de estados.
Observar que la x simboliza que para cualquier entrada (externa) siempre se va hacia el mismo estado ($e_1$) y se codifica con la salida $1$, como la salida de $e_0 \rightarrow e_1$ se codifica como 1, solo depende del estado en el que se encuentra la maquina por lo que practicamente nos encotramos en una *maquina de moore* 
![[Pasted image 20220912175923.png]]
Se hace la tabla de estados y se codifican en binario los estados asi como las salidas.

Se determina el numero de flip flops, en este caso 2 por el numero de bits requerido para representar los estados.

Se plantea la tabla de transiciones y salidas para generar el [[Circuitos combinatorios]] deseado.

![[Pasted image 20220912180117.png]]

Esto no es una tabla de verdad dado que hay inputs que aparecen varias variables en con distintos tiempos. En este caso para esto solo se "cambian" los nombres de las columnas $Q1_{n+1}$ y $Q0_{n+1}$

Por lo que se utiliza la formula del *T-flipflop*

![[Pasted image 20220912180524.png]]
 Determino los ouputs para $D_0$ y $D_1$ (recordar que cuando se construye un circuito combinatorio con varios ouputs se realiza el algortimo una vez para cada uno), faltaria hacerlo para ambas $S_x$ pero en este caso son identicos a las $D$.  