# SQL
#### From [[BBDD]]

## Group by Having:
La palabra reservada having exige que todo atributo de la tupla que aparezca en el select , o es utilizado para en dicho select dentro de una funcion de agregacion, o es parte de los criterios de agrupamiento.
Esto se exige con el objetivo de que *todo lo que aparezca en el select de una consulta que utiliza group by, refiera a todo un grupo y no solo a parte del mismo*.

Por ejemplo:
```sql
select *
from casts
group by casts.person_id
```
En esta consulta todos los atributos seleccionados (menos person_id) varian de tupla a tupla dentro del mismo grupo, pero como se tiene que retornar una unica tupla por grupo no se pueden pedir de esta manera, deberian ser utilizados como "parte de un todo" o, si se los quiere ver explicitamente, ser unicos para todo el grupo (por lo que se deberia agrupar segun ellos, lo que implicaria que aparezcan dentro del goup by).

En general, *SIEMPRE QUE USO FUNCIONES AGREGADAS SE ESPERA QUE SE RETORNE 1 TUPLA POR GRUPO*, si no hay clausula group by, entonces se asume que existe un unico grupo con todas las tuplas.
Por lo tanto esta consulta tambien es invalida
```sql
select count(*), movie_id 
from casts c 
```
Esto se debe a que `count` esta forzando a que se devuelva una unica tupla de un unico grupo, por lo que resulta imposible determinar el `movie_id` a retornar.
Dependiendo el manejador es posible que se retornen todas las ids segidas del valor del count, pero normalemente da error.

## Ejemplos spicy
primer parcial 2017
![[Pasted image 20220928030832.png]]
