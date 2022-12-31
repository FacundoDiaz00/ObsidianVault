
#### Notas: [[11-IntroEstratAccesoADatos.pdf]]

![[Pasted image 20221103050609.png]]

DBA: Administrador de la base de datos.
Usuarios parametricos: tipo bedelias, realizan consultas pre escritas.

## Organizacion y acceso a datos.

![[Pasted image 20221103051341.png]]
Los DBMS tipicamente se apropian de una particion del disco o un gran archivo y usan este espacio como "su disco"

Re implementan:
+ Estructuras de datos y sus algoritmos correspondientes
+ algoritmos de ordenacion
+ mecanismos de buffer y paginado

## Implementacion de consultas:

Primero se traducen a algebra, un join equivale a un doble for, etc

![[Pasted image 20221103051928.png]]

El calculo del JOIN requiere de $M*N$ accesos, lo cual es muy costoso.

### Indices:
![[Pasted image 20221103052054.png]]

![[Pasted image 20221103052437.png]]

![[Pasted image 20221103052558.png]]
### Sobre el uso de indices primarios.
Cuando se realiza una busqueda por indice primario, se recorre dicho indice hasta encontrar la entrada correspondiente al bloque donde se encuentra la tupla buscada.
En este caso si se buscan los datos de Luis, se recorre hasta lucia (bloque correspondiente) y luego dentro del bloque se busca a luis.


```ad-important
Cuando queremos buscar un dato determinado cargamos un bloque desde *el disco* a memoria y luego buscamos en memoria el dato que queremos.

Notar que *cualquier busqueda realizada en memoria en lugar de en disco requiere un tiempo despreciable*.

```

### Indice cluster por edad
![[Pasted image 20221110192052.png]]

De forma analoga se *ordenan en el indice las posibles edades*, en el caso donde la edad que se desea buscar sea la *última* del bloque, se deberá cargar también en memeoria al *bloque siguiente*.

**NOTAR QUE EN ESTE CASO LOS DATOS YA ESTAN PRE ORDENADOS POR EDAD.**

En caso de que no lo estén, se realiza lo siguiente:

![[Pasted image 20221103052956.png]]

En este caso cada entreada del indice apunta a una *lista de todas las tuplas* que tienen el valor determinado por la entrada.
Por ejemplo, la entrada 4 del indice, contiene un puntero a una lista de punteros hacia cada una de las tuplas que contienen 4 en el atributo segun el cual se realiza el indice.



![[Pasted image 20221103053021.png]]
![[Pasted image 20221103053818.png]]
Estructura tipica de las bases de datos actuales.

[[Procesamiento y optimizacion de consultas.]]