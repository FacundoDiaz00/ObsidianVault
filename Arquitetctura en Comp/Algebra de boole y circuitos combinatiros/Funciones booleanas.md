# Funciones Booleanas
#### From [[Algebra de boole]].

para n variables $G^n\to G$ 
Se pueden definir por tabla:
|   a | b   | c   | f   |
| ---:| --- | --- | --- |
|   0 | 0   | 0   | 0   |
|   0 | 0   | 1   | 0   |
|   0 | 1   | 0   | 0   |
|   0 | 1   | 1   | 1   |
|   1 | 0   | 0   | 0   |
|   1 | 0   | 1   | 1   |
|   1 | 1   | 0   | 1   |
|   1 | 1   | 1   | 1   |
O con las notaciones:
 1. Notacion $\Sigma$  (3,5,6,7) (en que filas de la tabla estandar la funcion da 1)
 2. Notacion $\Pi$ (0,1,2,4) (en que filas de la taba la funcion vale 0)
 Mediante expreciones
	 $F(a,b,c) = ab+ac+bc$

## Conectivas Binarias.
Estas son toas las posibles funciones booleanas de 3 variables.

| a   | b   | F_1 | F_2 | F_3 | ... | F_7 | F_8 | F_9 | ... | F_15 | F_16 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- | ---- |
| 0   | 0   | 0   | 0   | ... | ... | 0   | 0   | 1   | ... | 1    | 1    |
| 0   | 1   | 0   | 0   | ... | ... | 1   | 1   | 0   | ... | 1    | 1    |
| 1   | 0   | 0   | 1   | ... | ... | 1   | 1   | 0   | ... | 1    | 1    |
| 1   | 1   | 0   | 1   | 0   | ... | 0   |     |     |     |      |      |
(La tabla no es exacta)

Existen 16 en total.

## Construccion de funciones a partir de tabla.
n variables $x_1...x_n$

### Producto canonico
Es el and de todas las variables de forma directa o complementada.

$a_1\cdot a_2 ... \overline{a}_i  ...a_n$

### Suma de prodictos canonicos

Suma ponderada de todos los productos canonicos posibles donde cada termino tiene como coeficiente la valuacion de una funcion $F$.

$$
\overline{a}_1 \overline{a}_2 \overline{a}_3 ...\overline{a}_{n-1} \overline{a}_n \cdot F(0,0,...0)+$$
$$\overline{a}_1 \overline{a}_2 \overline{a}_3 ...\overline{a}_{n-1} {a}_n \cdot F(0,0,...1)+
$$

$$\vdots$$
$$a_1a_2a_3...a_n\cdot F(1,1,1...1)$$

Notar que los "$F(...)$" tienen valores predeterminados.

Se observa que esta funcion es equivalente a $F(a_1,a_2,...,a_n)$, dado un imput cualquiera, solo uno de los terminos tiene posibilidad de valer $1$ y por lo tanto posibilitar que la funcion tenga ouput $1$, esto ocurre si la funcnion $F$ para este input vale $1$.

Notar que es posible ignorar los terminos donde $F()$ vale 0.


## Conjunto de operadores logicamente completos.

Son aquellos conjuntos de operadores a partur de los cuales es posible formar cualquier funcion.

Por lo que se acaba de ver: $AND, OR, NOT$ forman un COLC.

Utilizando leyes de morgan se deduce directamente que $OR, NOT$ es tambien lun COLC, lo mismo se cumple para $AND,NOT$.

Luego utilizando solo $NAND$: 
	$a$ $NAND$ $a$ $=$ $\overline{a}$ 
	$a$ $NAND$ $b =$ $\overline{a}+\overline{b}$
Luego, como con NAND se puede representar $AND,NOT$ por lo que es logicamente complento, y de forma analoga para $NOR$.

## Metodos sistematicos de simplificacion.
### Metodo de Quine-McKlusky
### Diagramas de Karenaugh
Se plantea la tabla de la siguiente manera:
|c\ab     | 00  | 01  | 11  | 10  |
| --- | --- | --- | --- | --- |
| 0   |     |     |     |     |
| 1    |     |     |     |     |

(De forma que en cada "paso" solo cambie el valor de 1 variable)

Luego se determinan los lugares donde la funcion valga 1.
| c\ab | 00  | 01  | 11  | 10  |
| ---- | --- | --- | --- | --- |
| 0    |     |     | 1   |     |
| 1    |     | 1   | 1   | 1   |

Luego se deben cubrir los $1$ con la menor cantidad de los rectangulos mas grandes posibles.

  