# Representacion Interna de Datos.
### From [[Arquitetctura en Comp/Arqui]].
### Notas: [[Representacion Interna de datos.pdf]]


## Tipos de datos:
+ Tipo Caracter:

ASCII: American Standar Code Information Interchange (originalmente 7 bits en contenedor de 8 bits).

Se representa mediante:

Record.
ASCIIZ (posee caracter null al final.)

### Tipos de numeros:
#### Numero natural:
Representecion binaria: Representa al numero emdiante su expresion en binario.
Es capaz de representar numeros entre 0 y $2^n-1$.

Se conserva el orden.

Conserva las operaciones (siempre y cuando el resultado de la operacion es representable).

#### Numero Entero.
Representacion Valor y signo.
- El 0 aparece 2 veces.
- No mantiene orden.
- No conserva operaciones.

#### Representacion desplazamiento.
- Un solo 0
- Conserva el orden.
- no conserva operaciones.

#### Representacion Complemento a 2:
https://en.wikipedia.org/wiki/Two%27s_complement#Addition
Si el numero es mayor a 0 se lo representa en base 2.
Si es menor a sero se representa como el complemento a 2

$CompA2(x) = (compA1(x)+1) \mod 2^n$

Conserva orden y operaciones (multiplicacion se mantiene si se toma el resultado con los n bits menos significativos)

#### Representacion Decimal.
Se representa cada cifra del numero decimal.

Ej: $3 = 00110011$, $1=00110001$ (Son los simbolos de *caracter* de cada numero)

Para operar hay que ingorar los primeros $4$ $bits$, se puede realizar restando al numero en cuestion la represenracion del caracter de "$0$".

#### Reprecentacion Decimal Empaquetado (BCD).
Se representa un numero como la sucecion de las expresiones  en binario de cada digito del numero (en base 10), utilizando 4 bits por cada digito y otros 4 bits para indicar el fin del numero y el signo del mismo.

![[Pasted image 20221207152501.png]]


#### [[IEEE]].

## Overflow
El overflow ocurre cuando se sobrepasa el maximo numero representable.
En caso de la suma en complemento a 2 se puede identificar un overflow en caso de que los operandos tengan el mismo signo y el resultado de la suma el signo opuesto.

### Practico 2: [[Practico2]].
