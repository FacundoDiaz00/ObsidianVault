# Algebra relacional
#### From [[BBDD]].
#### Practico: [[Practico 3, Algebra relacional.]]
## Seleccion 

Permite obtener tuplas que cumplan una condicion determinada

Sintaxis:
	$\sigma_{<condicion>}(<relacion>)$
Da como resultado otra relacion con esquema igual que el de la entrada cuyas instancias del conjunto de tuplas cumplen la condicion.

## Proyeccion:
Tuplas con un cierto conjunto de atributos

Sintaxis
	$\Pi_{<lista_{}atributos>}(<Relacion>)$
	
Obs: no se admiten resultados repetidos (si dos tuplas son identicas a menos del id, y el id no esta en la lista de atributos, solo se obtiene una de las instancias).
Obs2: importa el nombre de la lista de atributos.

## Union

Union de dos relaciones tomadas como conjuntos de tuplas.

Sintaxis
	$(<relacion>)\cup(<relacion>)$
obs: las relaciones deben tener el mismo esquema (o un esquema compatible, tipos en el mismo orden)

## Diferencia
Obtiene la diferencia entre dos relaciones.
Sintaxis
	$(<relacion>)-(<relacion>)$
Misma observacion que en la union.


## Producto Carteciano
Obtiene todas las parejas posibles de tuplas.
	$(<relacion>)\times(<relacion>)$

Pueden quedar nombres de atributos repetidos, por lo que hay que referirse a ellos por su posicion.

## Operadores de Join

### Tita Join

Sean $R$ y $S$ dos relaciones
	$R\bowtie_{condicion}S$
	Es equivalente a realizar
	$\sigma_{condicion}(R\times S)$

### join natural

La operacion 
	$R*S$
	Es equivalente a 
	$\theta$-Join Con la condicion de igualdad entre los atributos de igual nombre y luego proyectar eliminand columnas de nombre repetido.

### Sobre la ejecucion del Join
Cuando se realiza un *Join* alcanza con que un par de tuplas cumpla la condicion para que el par pertenezca al resultado.
Es equivalente a formar el producto carteciano completo y tachar las tuplas que no cumplen la condicion.

#### Ejemplos:
Si quiero quedarme con los faricantes y los productos que *vende*, utilizo join natural, que me elimina del resultado las tuplas donde la id del fabricante no coincide con la id del fabricante de la venta.


## Operador Interseccion 
No se detalla pero existe

## Division

sean $R$ y $S$ dos relaciones con esquemas:
	$(A_1,...,A_n,B_1,...,B_m)$ y $(B_1,...,B_m)$
	La operacion $R\div S$ 
	Da como resultado una relacion con esquema $(A_1,...,A_n)$ 
	Y su contendio son las tuplas de $r(R)$ tales que su valor esta asiciado en $r(R)$ con TODOS los valores en $s(S)$
	
![[Pasted image 20220830032350.png]]

