[[SQL]], [[AlgebraRelacional]]
## Notas: [[12-ProcYOptimCons.pdf]]

![[Pasted image 20221103061901.png]]
![[Pasted image 20221103061915.png]]

![[Pasted image 20221103061958.png]]

Al aplicar las heuristicas, si se da el caso de que al poner a la izq las hojas con menos tuplas haya un join sin condicion entre dos "ramas" se cambia el orden para lograr que si haya join con condicion, manteniendo la hoja con menor numero de tuplas lo mas a la izq posible

Al transformar una consulta sql en el arbol canonico de consulta, se ponen las hojas del from de izq a der en el arbol.

![[Pasted image 20221103071404.png]]

![[Pasted image 20221103071413.png]]

![[Pasted image 20221103073115.png]]

## Implementacion de la seleccion

![[Pasted image 20221110194416.png]]

![[Pasted image 20221110201915.png]]

Notar que en el caso de las busqueda lineal lo unico quer tiene costo significativo es la lectura de cada bloque, una vez llevado el bloque a memoria, la busqueda dentro del bloque lleva un tiempo despreciable.

![[Pasted image 20221110195046.png]]
En el primer caso se lee un bloque (R) y luego por cada tupla de ese bloque obtengo otro bloque y junto la tupla de R con cada una de las nuevas tuplas.

+ $b_r$ es el costo de llevar a memoria cada boque de $R$
+ $n_r*b_s$ dado que por cada tupla de $R$ se deben traer cada uno de los bloques de $S$ (por cada tupla traigo cada bloque y realizo todas las combinaciones de esta tupla con tuplas del segmento obtenido)


En el segundo caso tomo un bloque R y un bloque S y realizo el "producto cartesiano" entre ellos. 
Si se tiene la posibilidad, es posible cargar varios bloques S o R a la vez y tabajar sobre ellos simultaneamente, para esto se utilizan buffers, notar que se requieren al menos 2 buffers prara almacenar a R y S, de eso el M-2

El primer $b_r$ corresponde a que es necesario traer todos los bloques de $R$
El siguiente termino corresponde a que hay que traer cada bloque de S una vez por bloque de R, o MENOS e caso de que se traigan varios bloques de R a la vez, por ejemplo si se traen 2 bloques de R cada iteracion, alcanzará con traer cada bloque de $S$, $b_r/2$ veces

![[Pasted image 20221110201800.png]]

![[Pasted image 20221118172558.png]]
Busqueda lineal es lo que hago cuando no tengo indices, ni ordenamiento


![[Pasted image 20221118172614.png]]
Notar que el index join requiere un indice sobre la tabla de la *derecha*, a su vez si el indice se tiene sobre varios atributos, por ejemplo  (saga_id, peli_id) entonces se podrá hacer index join con *saga_id y no con peli_id* ya que se toma el primer atributo del indice.

Notar que luego de realizar una BUSQUEDA LINEAL ($\sigma$) se pierden los indices por lo que luego de esto no se podrá realizar un index join.

