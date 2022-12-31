# Medidas informales de calidad.
#### From [[BBDD]].
## Semantica e los atributos.
- Debe ser facil explicar el significado.
- Hay que preguntarse: ¿Que significa que una tupla pertenezca a una relacion? que significa cada atributo exactamente?
- No combinar *atributos* de distintos tipos de *entidades* y tipos de vinculos en una sola *Relacion*
- 
## reduccion de valoes redundantes.
- Ademas del gasto de memoria esto provoca *anomalias en la insercion, eliminacion y/o modificacion*
- Esto corresponde a cuando valores en la tupla que deberian ser redundantes (ej: tupla con numero y nombre de departamento) no coincidan como deberian.
- 
## Reduccion de valores nulos
- Desperdicio de espacio.
- Significado poco claro:
	+ No corresponde nada a ese valor para esa tupla?
	+ No se sabe la informacion del atributo para esa tupla?
+ Complica las funciones agregados:
	+ cuenta para el count?


## No generacion de tuplas erróneas.
En casos donde la informacion que se quiera recuperar requiera de hacer un *join* de dos tablas que dependa de atributos que *NO* son *determinantes* se pierde informacion, dado que realizar el *join* causaria que se generen tuplas sin sentido.

