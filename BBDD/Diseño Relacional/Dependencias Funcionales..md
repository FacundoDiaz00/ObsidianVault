# Dependencias funcionales.
#### From [[BBDD]].
#### Notas: [[8-Dependencias_Funcionales.pdf]]
## DEF:
Una $df:X\rightarrow Y$ entre 2 conjuntos de atributos $X$ e $Y$, $X,Y\subset R$ especifica una *restricción* sobre las posubles tuplas que formarían una instancia $r$ de $R$. 

Para 2 *tuplas* cualesquiera $t_1,t_{2}\subset r$ se cumple: $t_{1}[X]= t_{2}[X] \rightarrow t_{1}[Y]= t_{2}[Y]$.

## DEF:
+ $F$ es el conjunto de $dfs$ que se especifican sobre un esquema $R$
+ $F+$ es el conjunto de todas las $dfs$ que se cumplen en instancias que satisfacen a $F$

## Reglas de inferencia para las $dfs$
![[Pasted image 20220916024456.png]]

## Calusura de $X$ bajo $F$ - $X+$
+ $X+$ es el conjunto de atributos determinados funcionalmente por $X$

### Algoritmo: Determinar $X+$ bajo $F$
```pseudocodigo
	X+ = X
	repetir
		viejoX+ = X+
		para cada df Y->Z en F hacer
			si Y subset de X+ entonces 
				x+ = X+ union Z
	hasta que (viejoX+ == X+)
```

## DEF:
Dos conjuntos de $dfs$ $E$ y $F$ son *equivalentes* si y solo si $E+=F+$

## DEF:
$F$ es minimal sii:
+ Toda $dfs$ en $F$ tiene un solo atributo a la derecha.
+ No podemos reemplazar ninguna $df:X\rightarrow A\in F$ por una $df:Y\rightarrow A$ donde $Y \subset X$, y seguir teniendo un conjunto de $dfs$ equivalente a $F$
+ No podemos quitar nunguna $df$ de $F$ y seguir teniendo un conjunto de $dfs$ equivalente a $F$
## DEF:
Un cubrimiento minimal de $F$ es un conjunto minimal $F_{min}$ que es equivalente a $F$ 
### Algoritmo para encontrar un cubrimiento minimal:
![[Pasted image 20220916030843.png]]
Observar que:
+ Paso 1 y 2 solo separar lados derechos.
+ Paso 3: nos fijamos si sobran atributos en el lado izquierdo de alguna $df$.
+ Paso 4: por cada $df$ nos fijamos si se puede deducir del resto de $dfs$ del conjunto. (alcanza con boservar los "lados derechos" repetidos).

### Practico: [[Practico 5 Dependencias Funcionales]].

