[[Procesamiento y optimizacion de consultas.]]

Sobre una bd se podrían ejecutar muchos procesos simultaneamente que interfieren unos con otros.
Por ejemplo, dos procesos que sobreescirben un mismo valor.


![[Pasted image 20221113065949.png]]
(en este caso T2 "no se entera" de las modificaciones realizadas por T1. En este caso el valor de X qeuda con un valor incorrecto.

## Transaccion.
A cada uno de los procesos concurrentes que se ejecuta sobre datos compartidosm se le llama *Transacción* si cumple con las popiedades *ACID*

+ *Atomicidiad*: Se ejecuta totalmente o no se ejecuta. (se ejecuta como si fuera una sola isntruccion)
+ *Consistencia*: Simpre nos lleva de un estado consistente a otro estado consistente.
+ *Aislamiento*: una transacción no debe interferir con otra.
+ *Dirabilidad*: los efectos de una transaccion deben ser permanentes sobre la base.


### Estados para gartantizar ACID

![[Pasted image 20221113070733.png]]

Si pasa por el estado de falla, entonces el resultado será identico al de nunca haber ejecutado la transaccion.

### Operacion.

+ $read_i(X),r_i(X)$: La transacción i lee el ítem $X$ de la baSE
+ $write_i(X),w_i(X)$: la transaccion i escribe el item X de la base.
+ $commit_{i}, c_i$: la transaccion i confirma que todas las modificaciones deben ser parmanentes.
+ $abort_{i,}a_{i:}$La transacción i indica que ninguna de sus modificacioens deben ser permanetnes en la base.

Una *transacción* será una *secuencia de operaciones*.

#### Rollback
Se llama rollback al volver al estado previo a la transaccion

### Manejador de transacciones.
Se encarga de recibir las operaciones recibidas desde los distintos procesos que ocurren y llevar esto a un *orden* de ejecucion que no viole ACID. A este orden se le llama *historia*.
Es capaz de ordenar las operaciones de un par de transacciones pero *no* cambiar el orden de las operaciones de una transaccion individual determinada.
El transaction manager puede transformar un commit con un abort si lo requiere.
![[Pasted image 20221113071640.png]]
En este caso se abortan ambas transacciones.



### Operaciones en conflicto.
Dos operaciones estan en conflico si cumplen a la vez:

+ Pertenecen a distintas transacciones.
+ Acceden al mismo item
+ Una es un write

### Historia completa
Historia Completa. Es aquella que cumple:  
-  tiene *todas las operaciones* de las transacciones involucradas.  
-  cualquier par de operaciones de la misma transacción, deben  
aparecer en la historia en el *mismo orden* que en la transacción.  
-  las operaciones en *conflicto* deben tener su *orden de aparición  
definido* en la historia.

### Def:
$T_1$ lee de $T_2$ si $w_2(X)$ está antes de $r_1(X)$ y entre medio:
+ no hay otro $w_j(X)$ tal que $c_j$ esté en $H$.
+ no está $a_2$.

(se escribe antes de que la otra lea, no se escribe entre la escritura y lectura y la escritura no es abortada)

## Historias Serializables y Recuperables  

+  Si las transacciones se ejecutaran siempre en forma  *serial*, entonces *no habría concurrencia* pero los datos  
siempre serían correctos.
+  Si las historias son *entrelazadas*, podría suceder que  queden *datos erróneos* que no se puedan corregir o que  si una transacción aborta otra también tenga que  abortar.

### Historia serializable
Es aquella que es *equivalente* a una historia seial con las misma transacciones.
![[Pasted image 20221113072944.png]]

## Testeo de seriabilidad por conflictos:
![[Pasted image 20221113073107.png]]

### Teo:
Una historia $H$ es serializable si su grafo de seriabilidad es acíclico.

## Historias recuperables y que evitan abortos en cascada

![[Pasted image 20221113073610.png]]
(si una transaccion utiliza un dato, entocnes el dato utilizado va a estar confirmado antes de que se libere el resultado que los utiliza)

![[Pasted image 20221113073901.png]]

![[Pasted image 20221113074048.png]]

## Bloqueo y desbloqueo

![[Pasted image 20221113074218.png]]

![[Pasted image 20221113074446.png]]

![[Pasted image 20221113074433.png]]

Estas condiciones no garantizan seriabilidad.


## 2PL
(Si se cumple se garantiza seriabilidad)

![[Pasted image 20221113074922.png]]

$T_1$ no cumple 2pl.
**Un read lock, es mad debil que un write lock**

Notar que 2PL aplica para *transacciones* (T). Si una *historia* esta formada por 2 transacciones que siguen 2PL, entonces esa historia es serializable.

![[Pasted image 20221113074956.png]]
![[Pasted image 20221113075052.png]]

+ **Conservador:**
	Se hacen los *locks antes* que cualquier otra cosa.
	
+ **Estricto:**
	Una vez que bloqueo *Write*, nunca vuelvo a desbloquear.
	
+ **Riguroso:**
	*Nada* se libera una vez lockeado.


## Recuperabilidad, EAC y Estrictas

### Recuperabilidad
Para que una historia sea recuperable es necesario que si una transaccion T2 lee de otra T1, entonces T1 hace commit antes que T2, esto se debe a que en caso de que T1 (escritora) aborte, T2 no habra aún realizado su commit el cual modificaría la base.
(Si leo un atributo modificado, quien modifica hace commit antes que yo, para darme tiempo a abortar también)


### EAC (Evita abortos en cascada)
Los abortos en cascada ocurren cuando una transaccion lee sobre una escritura realizada por otra cuando la que escribió aún no ha realizado commit .
(si voy a  leer sobre algo modificado, quiero que se haya realizado el commit)

### Estrctas
Una historia para ser estricta debe cumplir EAC.
Ninguna transacción lee o escribe hasta que todas las transacciones que escribieron ese ítem fueron confirmadas.


## Soluciones para DeadLocks

### Basados en TimeStamp

$TS(T)$ es un identificador para cada $T$ que cumple $TS(T_{i)}<TS(T_{j)}$ si $T_i$ comenzó antes de $T_j$.

Asumiendo que $T_i$ quiere lockear un item que $T_j$ ya tiene lokeado

+ *Wait-die*: si TS(Ti) < TS(Tj) (Ti es mas *vieja*), entonces *Ti* está autorizada a *esperar*. 
 Si TS(Tj) < TS(Ti) (Ti es mas *nueva*), entonces *Ti aborta* y es recomenzada más tarde con el mismo timestamp.
 (Si soy una transaccion mas antigua, espero a que termines, sino aborto y arranco despues con el mismo TimeStamp) (Si el viejo lo pide entonces tiene que esperar, si el joven lo pide tiene que abortar)

+ *Wound-wait*: si TS(Ti) < TS(Tj) , entonces Tj aborta y es recomenzada más tarde con el mismo timestamp. De lo contrario, Ti espera.
(Si soy una transaccion mas antigua, entonces vos abortas y arrancas mas tarde, sino Espero a que termines) (si el viejo lo pide entonces abortas, si el joven lo pide entonces espera)
+ Pueden producir *abortos y reinicios innecesarios*.


### Deteccion
+  Mantener el *grafo de espera* y si hay deadlock, “*seleccionar una victima*” y hacer que *aborte*.  
+  Util para *transacciones chicas* (que trabajan sobre pocos ítems) por poco tiempo.  
+  Si las transacciones son largas y trabajan sobre muchos ítems, se genera mucho overhead. Sería mejor usar prevención.

### TimeOut.  
+ Si una transacción espera por mucho tiempo, el sistema la  
aborta sin importar si hay deadlock o no.


### Problemas en Locks: Starvation  
+  Una transacción no puede ejecutar ninguna operación por un período indefinido de tiempo.  
+  Esto puede suceder por ejemplo, por un mecanismo de “selección de víctima” equivocado.  
+  Soluciones similares a las usadas en SO:  
	+  FIFO  
	+  Manejo de prioridades.  

+ Wound-wait y Wait-die evitan este problema.


## Control de Concurrencia Basado Ordenación de TimeStamps  

+  Cada transacción T tiene un timestamp TS(T)  

+  Cada ítem X, tiene 2 timestamps:  
	+  **Read_TS(X)**: el timestamp de la *transacción más joven que leyó el ítem*. (El timestamp más grande).  
	+ **Write_TS(X)**: el timestamp de la *transacción más joven que grabó* el ítem.

+ La idea consiste en ejecutar las *lecturas y escrituras de acuerdo al orden de los timestamps*. Si el orden se viola, entonces se aborta la transacción.

![[Pasted image 20221114080134.png]]
En el primer caso, si una transaccion antigua trata de escribir un valor con el que ya interactuó una mas joven, la transaccion debe abortarse y comenzar con un nuevo TimeStamp. Si la transaccion que intenta escribir es mas joven se ejecuta el write y se actualiza el Time_TS(X).

Si una transaccion antigua intenta leer un valor, de la misma forma se cancela la transaccion y se reinicia con un nuevo TS. En otro caso, se realiza el Read y se actualiza Read_TS(X)

## Control de Concurrencia Multiversión  

+  Algoritmos anteriores, demoran lecturas en forma innecesaria por locking o por abortos sucesivos de una transacción.  
+  Una Solución: *Mantener varias versiones de cada ítem y elegir la correcta*.  
	+  Ventaja: Las lecturas no tienen porqué esperar.
	+  Desventaja: Se necesita espacio extra para almacenar las versiones de cada ítem. Podría no ser demasiado relevante de acuerdo a los esquemas de recuperación que se utilicen.

![[Pasted image 20221114081050.png]]

En el caso del write, si una transaccion mas joven que yo ya leyó lo que una mas antigua que yo escribió, entocnes debo abortar (las transacciones jovenes utilizan los valores seteados por la antiuga, por lo que no puedo modificar o crear una version mas nueva), en otro caso, se CREA un nuevo valor registrado para el dato cuyos ambos timeStamp son el mio. 

En el caso de read, *Leemos la escritura MAS NUEVA* tal que no sea mas nueva que yo, luego actualizo el valor mas reciente de lectura con el maximo entre mi lectura y la maxima anterior.

## Concurrencia en la Inserción y Eliminación.  
+  Eliminación:  
	+ Locking: se lockea en forma exclusiva  
	+  Timestamp: hay que garantizar que ninguna transacción posterior a la que elimina el registro haya leído o escrito el elemento.  
+  Inserción:  
	+  Locking: Se crea un lock, se inserta un registro y se libera en el momento adecuado según el protocolo.  
	 + TimeStamp: Se asigna el TS(X) como Write_TS y como Read_TS(X).