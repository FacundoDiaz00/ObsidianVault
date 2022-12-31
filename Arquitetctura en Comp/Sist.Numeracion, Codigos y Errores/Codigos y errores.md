# Codigos y errores.
## From: [[Arquitetctura en Comp/Arqui]]
## Notas: [[Codigos y errores.pdf]]

### Ejemplo de codificacion: Frutas (de Openfing 2)
| Fruta   | Codigo |
| ------- | ------ |
| Naranja | 000    |
| Manzana | 001    |
| Uva     | 010    |
| ...     | ...    |
| Fruta   |        |

En este ejemplo, dado que se utilizan 3 bits, se pueden representar hasta $2^3$ frutas.

## Distancia entre codigos:
$\text{Def: Numero de bits que de se deben modificar para transformar un codigo en otro.}$

## Distancia de un sistema de codificacion:
$\text{Def: Es el minimo de las distancias de los codigos del sistema.}$
### Nota: 
- Mientras mayor sea la distancia de un sistema de codificación, mayor es la capacidad del sistema de manejar errores.
## Representacion grafica para un caso mas general:
![[Pasted image 20220729021239.png]]

## Deteccion y correccion de errores:
Para la deteccion de errores es necesario que $d > e$. (cuando esto ocurre significa que en caso de haber $e$ errores en el codigo $A$ podemos estar seguros de que el codigo no se transformara en $B$.)

Para la correcion de errores es necesario que $d>2e$, debido a que en este caso dado un codigo que contiene errores, podemos saber a cual de las dos esferas pertenece y, por lo tanto, cual era el codigo original.

## Bits de Redundancia:
Sea un caso donde se desee:
+ Codigo de $n$ $bits$.
+ $1$ $bit$  posible de error.
+ $r$ $bits$ de redundancia.

### Se desea hayar una condicion necesaria para $r$.
   Para correccion de errores es necesario que se cumpla $2^r>n+r$
   (La cantidad de pocisiones que pueden ser identificadas mediante los bits de redundancia debe ser mayor a la cantidad de bits total del codigo, incluyendo mensaje y redundancia)

### Ejemplo: no se puede corregir errores, si identificar.
000 0
001 1
010 1
011 0
100 1
101 0
110 0
111 1
### Sistema 2 de 5: [[Entrelazado 2 de 5]]

### Sistema de [[Paridad en codigos y errores.]]
### Sistema de [[Codigos de Hamming]].

### Sistema de [[Suma De verificacion y CRC]].