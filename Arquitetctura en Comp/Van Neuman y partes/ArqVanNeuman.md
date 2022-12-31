# Arquitectura Van Neuman
#### From: [[Arquitetctura en Comp/Arqui]].
#### Notas: [[13-von_neumann-2011-4.2.pdf]]

## CPU
Es una [[Memoria]] ROM de isntrucciones basicas implementadas como [[Circuitos combinatorios]].

## [[Memoria]]
En este contexto refiere a una memoria RAM.
Corresponde a el [[Circuitos Secuenciales]] que permite que la maquina pueda, al menos a nivel teórico, realizar uan solucion para cualquier problema.

## E/S
Perisfericos, elementos de entrada y salida para interaccion con el usuario.



## Caracterizacion de una computadora Van Neumann.

### Conjunto de operaciones del cpu
Pueden ser de mayor o menor nivel, incluir mas o menos.
Existen implementaciones con minima cantidad de operaciones (RISC) o mas extensivas o complejas (CISC).

### Formato de Instruccion.

Las intrucciones que se desea llamar deben estar codificadas de una manera determinado
Ej
	operacion|operando1|operando2|modos

#### Largo de instrucciones
Ademas, por ejemplo RISC utiliza instrucciones de largo fijo, en contraparte con las instrucciones de largo variable de CISC, tener largo de instruccion fijo aumenta la velicidad/efeciencia con la que se ejecutan las instrucciones.

#### Cantidad de operandos.
Existen arquitecturas de 2 o 3 operandos.
En arquitectura de 2 operandos el resultado de la operacion se guarda en uno de ellos.

En las de 3 se almacena en la tercera.

Risc utiliza 3 operandos.
Cisc depende.

### Set De Registros
Conjjnto de registros (memoria de alta velocidad que se encuentra fisicamente mas cerca al cpu, por lo que es memoria de mayor velocidad)

#### Cantidad

#### Cualidad
+ Uso general
+ Personalizados
	+ Acumulador
	+ Base
	+ Contador

(Los registros tienen funciones especificas, no se pueden utilizar para cualquier cosa).

Risc usa Registros de Uso general.


### Modos de direccionamiento.

Directo, el valor del operando viene en la propia instruccion.

Inmediato, la id del registro donde esta el operando viene el operando.
