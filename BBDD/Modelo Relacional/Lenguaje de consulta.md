# Lenguaje de consulta
#### From: [[Operaciones en una base de datos.]], [[BBDD]].

## Intro.
La idea vbasica de los lenjuages de consulta es tomar las tablas de las base y construir nuevas tablas al vuelo.

# Calculo Relacional.
Es la familia de lenguajes de cosnulta sobre un *modelo relacional*.

Basafos en fórmulas de locuva de primer orden para defunir conjuntos.

Especificacion por comprensiopn de un conjuto de tuplas.

## Dos sublenguajes:

+ Calculo de tuplas: varibles de tipo tula (universo formado por tuplas)
+ Calculo de dominio: variables por valor de atributo, el universo esta formado por valores individuales.


## Sintaxis del calculo de tuplas:
Las expresiones del calculo son de la forma:
	$<t_1,...t_n>/\phi(x_1,...,x_n)$ donde:
	$t_i$ son terminos de la forma $x_iA_k$ o bien $c_i$.
	Con $x_i$ variables libres de $\phi$
	$A_k$ atributo de la tabla para el que $x_i$ representa una tupla.
	$c_i$ es una cosntante de algun dominio.
### Definicion inductiva de $\phi$
1. $x_i$ es un termino, si $x_i$ es una variable.
2. $c_i$ es un termino, si $c_i$ es una cosntante de algun dominio.
3. $x_iA_i$ es u ntermino, si $x_i$ esuna variable y $A_i$ es un nombre de atributo.

Hay dos tipos de terminios:
	Atomicos ($c_i$ o $x_iA_j$)
	No atomicos: $x_i$ (variables)
### Formulas, def inductiva.
![[Pasted image 20220826210521.png]]

### Condiciones de verdad de las formulas.
1. $\phi$ de la forma $P(x_i)$ es verdadera si hay alguna tupla $t$ que pertenezca a $P$.
2. La forma $t_i <op> t_j$ es verdadera si se cumple la rel especificada por op.

### Ejemplo:

Ventas que fueron por un precio mayor a 50.000.

	$\{t| VENTAS(t) \wedge t.precio > 50000\}$
	

## Dominio de una expresion CRT

Conjunto de valores que aparecen como constantes en la expresion, o bien exsisten en cualquier tupla de las relaciones a las que se hace referecnia en la expresion.
(Todas las tuplas en alguna de las relaciones de la expresion + tuplas constantes en la expresion)

### Formulas seguras.
Una expresion CRT es segura si todos los resultados pertenecen a su dominio.

## [[Calculo de dominios]].
 $$\{m / Movies(m) \land (\exists r)(references(r) \land r.referenceTo = m.movieId) \land (\forall r)((references(r) \land r.referenceTo = m.movieId) \rightarrow (\exists mg_1)(\exists mg_2)(movieGenre(mg_1) \land movieGenre(mg_2) \land mg_1.genereId = mg_2.genreId \land mg_1.movieId = m.id \land mg_2.movieId = r.referencedBy))\}$$

$$\{m / Movies(m) \land (\exists r)(references(r) \land r.reference\_to = m.movie\_id) \land (\forall r)((references(r) \land r.reference\_to = m.movie\_id) \rightarrow (\exists mg_1)(\exists mg_2)(movie\_genre(mg_1) \land movie\_genre(mg_2) \land mg_1.genere\_id = mg_2.genre\_id \land mg_1.movie\_id = m.id \land mg_2.movie\_id = r.referenced\_by))\}$$

$$\Pi_{\$1,\$2}(\Pi_{\$6,\$14,\$5,\$13}(CASTS \bowtie_{\$1 = \$5} MOVIES \bowtie_{\$2 = \$13} PEOPLE)-(\Pi_{\$10,\$18,\$9,\$17}(CASTS \bowtie_{\$1 = \$5 \land \$2 \neq \$6}CASTS \bowtie_{\$1 = \$9} MOVIES \bowtie_{\$2 = \$17} PEOPLE))$$
