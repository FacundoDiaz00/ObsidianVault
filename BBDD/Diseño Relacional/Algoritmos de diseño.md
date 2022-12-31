# Algoritmos de dieño.
#### From: [[BBDD]].

## Definiciones iniciales:

+  $R=(A_{1},A_2,...,A_N)$ , contiene a todos los atributos de la $BD$
+ $D=(R_{1},R_2,...,R_m)$ , es la descomposición que se obtiene mediante los algoritmos, se cumple que la union de los $R_i$  es igual a $R$

## Proyeccion de un conjunto de dependencias sobre un Esquema de Relacion.
### $\Pi_{R_i}(F)$
Dado un conjunto de $dfs$ $F$ sobre $R$, la *proyección* de $F$ sobre $R_i$ ,  ($\Pi_{R_i}(F)$) es:
	El conjunto de $dfs$ en $F+$ tal que los atributos de tales $dfs$ esten en $R_i$.

![[Pasted image 20221022025155.png]]
Notar que se le hace el ()^+ a la union de las dfs proyectadas



## Algoritmo para $3NF$ que garantiza la preservacion de $dfs$.
 ![[Pasted image 20220917023721.png]]

## Join sin perdida.
#todo 
- [x] Entender esta def
```ad-info
Una descomposición $D = (R1, R2, ..., Rm)$ de R  
tiene la propiedad de $JSP$ respecto al conjunto  
de $dfs$ $F$ sobre $R$, si por cada instancia de  
relación $r$ de $R$ que satisfaga $F$, se cumple lo  
siguiente:  
 $(\Pi_{R1}(r), ..., \Pi_{Rm}(r) = r$
```
**(el join natural de todas las tablas que tengo me reconstruye exactamente la instancia de la tabla)**
![[Pasted image 20221022025256.png]]

Propiedad:
	$D=(R_1,R_2)$ de $R$ tiene $JSP$ respectio a $F$ sobre $R$ $sii$:
		- la $df$ $(R_1 \cup R_{2})\rightarrow (R_1-R_2)$ esta en $F+$
		o
		- la $df$ $(R_1 \cup R_{2})\rightarrow (R_2-R_1)$ esta en $F+$
 

![[Pasted image 20221022031649.png]]
Al joinear las tablas de abajo se generan tuplas nuevas, dado que un par de proyectos que compartan LUGARPR pueden existir, y en el join se crearian tuplas donde empleados quedan asociados a proyectos a los que no pertenecen originalmente dado que dichos proyectos comparten ubucacion con un proyecto donde el empleado SI trabajaba.
![[Pasted image 20221022032029.png]]
Observar que Nieto, Ramon K no trabaja originalmente en Reorganizacion

![[Pasted image 20221022025321.png]]

![[Pasted image 20221022025340.png]]

![[Pasted image 20221022025359.png]]

