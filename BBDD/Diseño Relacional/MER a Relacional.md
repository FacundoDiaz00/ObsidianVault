#### From: [[BBDD]].

## Entidades:
**Por cada entidad se crea una tabla.**
+ Por cada atributo **simple** se crea un atributo en la tabla.
+ Para cada atributo estructurado, un atributo por cada hoja.
+ Atributos multivaluados.. mas adelante.
La clave primera va a ser alguno de los atributos determinantes.
Si el unico atributo determinante es multivalorado, probablemente se tendrá que agregar un atributo inventado para usar de identificador.

Si el atributo determinante es estructurado, se deberan subrayar todos los atributos correspondientes a la estructura. Subrayar varios atributos indica que se requiere de **todos** ellos para determinar el resto.

Luego agregar restricciones que aseguren el uso correcto de las calves foraneas.
Ej:
	$Personal(cedula,nombre,edad,ciudad,valle,nro)$
	$Telefonos(cedula,telefono)$
	Hace falta agregar:
	$\Pi_{cedula}(Telefonos)\subset \Pi_{cedula}(Personal)$


## Relaciones.
**Para cada relacion binaria con cardinalidad se crea una tabla donde:**

+ Se colocan las calves primarias de las tablas que representan a cada una de las entidades participantes
+ SI existen atribuors en la relación se tratan como si fueran los de una entidad.
+ Agregar dependencias de inclusion por cada entidad participante.

### **Relaciones binarias ($1:N$):**
$1:N$ sin totalidad del lado $N$:
+ **se trata como una $N:N$** exepto por la clave primaria de la tabla de la relación, que es la calbe del lado $N$.
+ Ej: si una persona trabaja en una sola sala y en cada sala trabajan n personas, la tabla trabajan posee identificadores de la sala y de la persona **y cada tupla es identificada por la id de la persona**
$1:N$ con totalidad del lado N
+ No se crea tabla para la relación y se agrega la clave de la tabla de la entdiad del lado 1 en la tabla de la entidad del lado N. (como todo elmento del lado N esta asociado a uno del lado 1, lo agrego directamente a la tabla)

## Entdidad es debilies

**Por cada entidad debil se crea una tabla.**
+ se preicede con las relaciones 1:N y totales del lado N, sin crear tabla de relacion.
+ Se agrega la clave primaria de la tabla de la entidad fuerte en la tabla de la entdiad debil
+ La clave primaria sera la de la entdiad fuerta + atributo/s que representa al identificador principal

## Agregaciones.
Para la relacion que conecta la agregacion con otra entidad se agrega una tabla con el identificador de la tabla de la relacion que forma la agregacion y el identificador de la otra entidad. 

## Categorizaciones.

1. Una tabla para el conjunto grande y una para cada subconjunto, esta ultima referencia a la super entidad y agrega sus atributos propios.
2. Caso categorizacion total : Una tabla para cada una de las subentidades que contiene todos los atributos de la superentidad y los propios, luego agregar una vista.... 
3. Caso categorias disjuntas :  agregar todos los atributos opcionales (podrian quedar vacios) y un atributo de tipo. 
4. poner una tabla con todo y un atributo booleano para cada categoría.

