[[ArqVanNeuman]]
## Principio de localidad

### Localidad temporal
Cuando se  usa un dato, es probable que dentro de poco se vuelva a utilizar

### Localidad Espacial
Cuando se usa un dato, es probable que dentro de poco se utilize alguno cercano en memoria

![[Pasted image 20221112072159.png]]

## Tiempos de la memoria

#### Tiempo de acceso:
Tiempo entre dar direccion y devolver el dato.

#### Tiempo de recuperacion
Tiempo requerido para realizar una nueva lectura tras haber ejecutado otra.

#### Tiempo de ciclo
Suma del tiempo de acceso y el de recuperacion.

### Bancos de memoria.
Al tener varios "chips" de memoria es posible que luego de leer en uno de ellos se puede leer en el otro mientras el primero se recupera

## Memoria cache.

+ La memoria cache funciona como un intermedio entre la principal y los registros. 
+ Esta formada por líneas (unidad de transferencia), usualmente es del mismo tamaño que del bus de datos, para así obtener una linea entera a la vez.
+ Cuando se logra un hit, se carga en la cache los bytes cercanos (se cargan creo que en una línea)

### Política de Escritura  
Hasta ahora hemos analizado como se comporta la memoria cache en la operación de lectura, pero también debemos analizar qué pasa cuando la CPU escribe en la memoria.  
En las operaciones de escritura (write) existen dos grandes estrategias write  
through y write back. La primera (*write through*) implica que, de existir un hit, la operación de *escritura se hace en la memoria cache y también en la memoria principal*. En la segunda (*write back*) en el caso del hit *la escritura se realiza solamente en la memoria cache*.

Naturalmente la estrategia *write back permite un mejor desempeño* del sistema en escritura, pero tiene la complejidad adicional de determinar si es necesario *actualizar la memoria principal con el contenido de una línea de cahe que va a ser reemplazada* como consecuencia de un miss, si es que el bloque tuvo algún cambio desde que se trajo a la cache. También tiene la tarea adicional de velar por la *coherencia de la cache*, aspecto que veremos más adelante.

## Funciones de correspondencia

Determinar en que *lugar del cache* se va a almacenar el contenido de una *posicion de la memoria* principal
Por  tanto la función de correspondencia establece para cada bloque de memoria cuales son las líneas posibles de ser utilizadas en la cache para almacenarlo.
### Correspondencia directa
![[Pasted image 20221112072359.png]]
![[Pasted image 20221112072412.png]]![[Pasted image 20221112072433.png]]
![[Pasted image 20221112074838.png]]
Ejemplo:
Cache de 64KB

Para identificar a un byte se requiere de:
+ Un byte al que quiero acceder (byte DENTRO DE LA LINEA), la cantidad de bits de esta parte depende del tamaño de línea
+ La identificacion de la línea dodne esta el byte
+ El TAG que identifica en que "bloque" está la línea seleccionada 

Por esto cuando se almacena en la cache un alínea se debe almacenar también cual es el TAG corresponiente a la misma

En esta representacion es posible que se requiera sobreescribir una linea en la cache aunque esta memoria tenga aún espacio libre

### Full Associative

+ Utiliza un tipo de *memoria especial*, la cual permite ubicart en memoria la línea de de cache a partir del valor del tag.
+ Almacena cualquier linea de la principal en cualquier linea de la cache.
+ La direccion de memoria se interpreta como *un tag y un word*
+ Un *bloque de memoria* principal se puede cargar en *cualquier línea* de la cache
+ Cada tag identifica un bloque. 
+ Cada tag debe ser examinado para ver si hay coincidencia
![[Pasted image 20221112075034.png]]

Para cada identificar cada linea almacenada en cache se requiere de:

Un tag que identifique el bloque de la memoria principal del que proviene la línea.
Este requierre de tantos bits como sean necesarios para representar valores ten grandes como el *numero de bloques de la memoria*.

Un Byte que identifique una posicion en la línea requiere tantos bytes como sean necesarios para identificar entre (Cantidad de bits por líena/Cantidad de bits por palabra almacenada).
Se calcula primero el largo del campo "Byte" y se dedican el resto de bits disponibles para la TAG



## Asociativa por conjuntos de N-Vias

Solucion intermedia entre las dos anteriores.
Se tienen N "bloques" de cache, para cada línea de memoria que se quiera almacenar en la cache se deberá elejir un "bloque" (izquierda de la imagen) y luego almacenarla de forma análoga a la directa dentro de ese bloque 
![[Pasted image 20221112080747.png]]
Cada línea de la memoria principal tiene N posibles lineas de cache donde puede ser almacenado (el caso N=1 es identico a correspondencia directa).

Se requere de:
+ Tag: cada tag identifica la línea, al intentar leer se provee una tag, se compararán simultaneamente la tag provista con las tags almacenadas en cada uno de los N "bloques" de cache (N comparaciones que como en el caso de Full associative se realizan simultaneamente). At the end of the day, este dato se utiliza para identificar el bloque de cache a leer
+ Identificador de conjunto, da la distancia entre el comienzo del "bloque de cache" y la línea almacenada que se quiera leer.
+ La ubicacion dentro de la línea del byte espeficico a leer.

## Algoritmos de Reemplazo
Cuando hay miss hay que leer un nuevo bloque de memoria cache, hay que decidir que lína de caché utilizar en caso de que haya mas de una opción.
En el casso de correspondencia directa no hay algoritmos de reemplazo.
En los otros dos casos he de elejir cual pocision de cache se utilizará.

+ LRU (least reciently used)
+ LFU (least frequently used)
+ FIFO
+ RANDOM (pseudo)

## Problema de la coherencia del Cache

El problema de la cache de memoria es la que aparece debido a que la cache posee una copia de la memoria.

Es posible que ocurra una inconsistencia logica entre ambas memorias en los casos donde NO solamente la CPU accede a la memoria principal.
Existen 2 des estos casos:
+ DMA: Intercambios grandes de informacion entre memoria y i/o sin intervencion de la CPU. 
	+ Caso 1: se escribe en memoria sin actualizar la cache. Este problema se soluciona mediante *Bus snooping*, si se detecta una situacion como esta se pone en 1 en *"dirty bit"* indicando que esa pos de memoria esta desactualisada por lo que la lectura de esta memoria dará miss hasta que se actualize.
	+ Caso 2: se lee la cache cuando es posible que esta no este actualizada con respecto a la principal. Esto depende de la política, el problema surge en el caso de Write back. *En este caso el bus snooping actualiza el dato en cache*. 
+ Multiprocesadores: Dos cpus, cada una con su cache, que comparten una memoria principal. 

Para el caso del cache con write back, si el problema ocurre en una *lectura*, el problema se *resuelve deteniendo el DMA* para actualizar la memoria con el contenido de la caché. Si se trata de una *escritura del DMA*, el problema  
se *resuelve invalidando la entrada del caché* y el *próximo acceso al bloque producirá un fallo* (“miss”) provocando la actualización de la cache.

Se dan los *mismos problemas* que suceden al usar DMA, cuando un procesador lee o escribe en bloques de memoria almacenados en la cache de otro procesador y además, en el caso de *write-back*, se puede dar la situación que el mismo bloque de *memoria esté simultáneamente en más de una cache y se desincronizará su valor cuando se escribe en las caches*.  

