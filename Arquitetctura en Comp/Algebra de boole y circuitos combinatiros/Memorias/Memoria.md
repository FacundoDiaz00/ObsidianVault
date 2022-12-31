# Memorias
#### From [[Arquitetctura en Comp/Arqui]]
#### Notas [[memorias Rom.pdf]], [[NotasFlipFlop.pdf]] [[Contadores.pdf]] [[Ram.pdf]]
#### [[Practico memorias]].

## Memorias Rom

Una rom de 8Kbits puede tener distintas formas:

+ 1Kx8 (1k palabras de 8 bits)
	Necesito una cantidad de inputs capaz de distinguir entre 1k opciones distintas (2^10 = 1024).
	Necesito 8 bits de ouput.
	(observar que necesariamente se debera repetir el mismo ouput para varias entradas distintas)
	

+ 4Kx2 (4k palabras de 2 bits)
	Necesito una cantidad de inputs capaz de distinguir entre 4k palabras (2^12 = 4096)
	Necesito 2 bits de outputs.
	
	(observar que necesariamente se debera repetir el mismo ouput para varias entradas distintas, incluso mas ouputs repetidos que el ejemplo anterior).

En general tener mas palabras implica tener un array con mas entradas.
Por el contrario tener palabras de mas bits implica que el universo de los valores posibles que puede tomar cada elemento del array es mayor.

## Chip select

![[Pasted image 20220822182815.png]]
![[Pasted image 20220905030541.png]]
La entrada $A_{10}$ indica de que chip tomo la salida, el mux funciona como la identidad si esta "seleccionado" y ouputea ceros sino.
![[Pasted image 20220905030823.png]]
version sin los *MUX* cajanegreados, obervar que $A_{10}$ en 0 es necesario para que los ands del chip de abajo tengan ouput distinto de 0, y lo opuesto para el de arriba.
![[Pasted image 20220905031123.png]]
Usando chip select te ahorras los mux.

## Ouputs Enable.
Es otro input en el chip, si esta en estado 0, la salida pasa a modo de alta impedancia lo que implica que la salida no esta en ningun estado logico.

## Circuitos Asincronicos
- [[Flipity-flopityflop]]
- [[Contadores]]

## Memorias RAM
Una memoria SRAM, por Static Random Access Memory, es una memoria contruída en base a un  
arreglo de flip-flops tipo D. Típicamente poseen m entradas de dirección y n entradas/salidas de datos,  
para un total de 2m palabras de n bits.  
Una memoria DRAM por Dynamic RAM, es una memoria construída en base a un artilugio electrónico  
consistente en aprovechar la capacidad parásita de los transistores para almacenar una carga eléctrica  
que representa el valor del bit. Los bits se organizan en una matriz, por lo que para acceder a un bit es  
necesario proporcionar la fila y la columna, lo que se hace de a uno por vez utilizando las entradas de  
direccion y las de control CAS y RAS.  
Algunas de las diferencias son:  
- Las SRAM son más rápidas que las DRAM.  
- Las SRAM se organizan como un arreglo de palabras de n bits, mientras que las DRAM como una  
matriz de bits individuales.  
- Las SRAM mantienen el valor del bit mientras tengan energía eléctrica, mientras que eso no alcanza  
para las DRAM que además necesitan de ser leídas periodicamente para reconstruir el valor de los bits  
almacenados (refresh).  
- Las DRAM son más densas que las SRAM (aprox: 1 transistor por bit vs 6 transitores por bit).  
- Las SRAM son mas caras que las DRAM.