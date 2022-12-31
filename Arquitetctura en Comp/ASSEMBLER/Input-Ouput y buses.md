# Input/Ouput
#### From [[ArqVanNeuman]]
#### Notas: [[InputOuputNotas.pdf]]
La entrada/salida actua como interfaz entre:
- Porogramas que ejecuta la [[CPU]] en base a las instrucciones y los datos almacenados en la memoria.
- Dispositivos que permiten interactuar con el mundo fisico (perisfericos).

Permite introducir en el sistema y presentar el resultado del proceso realizado al ser humano.

# Buses:
La conexion entre dispositivos de e/s, memoria y cpu se realiza mediante "lineas" que comunican tipos de informacion, esta agrupacion se llama *bus*.
Se comunican tres tipos de informacion:
+ **Direccion**
		Transportan *direcciones de memoria* o E/S a ser accedidas durante la transferencia.
		Transporta informacion que permite *identificar las posiciones de memoria a leer ó escribir* y/o las entidades de E/S con las que se va a interactuar.
+ **Datos**
		Transmite informacion entre los diferentes componentes conectados.
		transporta los *datos leídos o a escribir* ya sea en la memoria o  
		en los dispositivos de E/S (traspaso de información entre los sub-sistemas)
+ **Control**
		Transporta *señales que controlan el uso del bus* y la comunicacion sobre el mismo.
		Algunas señales tipicamente presentes en este bus son:
+ *Memory_Read*: indica una operacion de lectura sobre la memoria.
+ *Memory_Write* (indica una operación de escritura sobre la memoria)  
+ *I/O_Read* (indica una operación de lectura sobre la entrada/salida)  
+ *I/O_Write* (indica una operación de escritura sobre la entrada/salida)  
+ *Bus_Request* (indica que un sub-sistema desea tomar control del bus  
para iniciar una transferencia)  
+  *Bus_Grant* (confirma que el bus está disponible para quien lo solicitó)  
 + *Transfer_ACK* (confirma la recepción de una transferencia de  
información)  
+ *Interrupt_Request* (indica un pedido de interrupción hacia un sus-  
sistema)  
+ *Interrupt_ACK* (confirma la aceptación del pedido de interrupción)  
+ *Clock* (sincroniza las actividades del bus y sus señales)  
+ *Reset* (fuerza el reset de todos los componentes conectados al bus)

En general un bus está definido por un conjunto de características que incluyen:  
+  Especificaciones *mecánicas* (conectores)  
+  Especificaciones *eléctricas* (niveles de voltajes y/o corriente), bits de dirección y  
de datos y consideraciones de "timing" (tiempo) de las señales involucradas  
incluyendo el reloj de sincronismo  
+  *Protocolo* de comunicaciones


Según sea el *tamaño* del sub-bus de datos se habla de buses de 16, 32 o 64 bits.
También caracteriza a un bus si el sub-bus de datos es *separado del sub-bus* de direcciones o está *multiplexado en el tiempo* con él.  

En particular estas dos características, unidas a la frecuencia del reloj utilizado para el sincronismo, determinan la capacidad de transferencia de información del bus.

### Tipos de buses:
+ **Bus simple:**
	Implementan la filosofia *"Master-Slave"*
	+ Existe una sola entidad que controla el uso del bus (Master), tipicamente la [[CPU]].
	+ Las entidades "esclavas" ue deseen utilizar el bus tienen que ser *habilitadas por el master*.
	+ El master utiliza *tecnicas de consulta* para determinar si una entidad esclava desea hacer una transfer, o bien *la entidad esclava avisa* de que quiere hacerlo (ej: pedido de interrupcion)
+ **Bus Inteligente:** 
	+ *Cualquier* entidad conectada tiene *capacidad de ser master*.
	+ En caso de que varias entidades quieran usar el bus, se realiza una competencia por su uso, resuelta por un *mecanismo de arbitraje*.
	+ **Arbitraje Centralizado** (jerarquico): Hay una entidad (normalmente CPU) con *mayor jerarquia*, es responsable de asignar el control del bus. La entidad interesada en utilizar el bus le avisa de este interés ("*bus request*") y el árbitro la habilita a utilizarlo ("*bus grant*")
	+ **Arbitraje distribuido** (equitativo), Se aplica un *mecanismo de arbitraje* que determina cuál de los contendientes por el uso del bus tendrá el control del mismo.
#### Otra categorizacion:
+ **Internos:** Conecta sub sistemas dentro de la "frontera del sistema", ej: Bus de memoria (CPU con bancos de memoria)
+ **Externos:** Sub sistemas fiera del sistema, EJ: usb (discos, impresoras, mouses, etc)

### Buses de expansión
Permiten conectar placas de ciruito adicionales.

## Perisfericos:
Transductores: interaccion con el usuario
Almacenamiento: discos magneticos, opticos, cintas, disquettes,etc.
Comunicacion: modem, etc

## Controladores de entrada y salida

La arquitectura de E/S maneja el concepto de “controlador de E/S”. Un controlador de E/S es la parte del periférico que contiene su inteligencia y por tanto lo “controla”

En la actualidad la parte mecánica del dispositivo y la inteligencia que lo controla están en el mismo gabinete, o al menos la inteligencia está distribuida entre el gabinete del periférico y el gabinete de la computadora. 
Dos ejemplos de casos extremos pueden ser por un lado un monitor gráfico (la caja del periférico tiene casi ninguna inteligencia vinculada a la generación de las imágenes que muestra y toda la inteligencia se concentra en el “controlador de video gráfico” que reside en el computador) y por el otro lado una impresora láser (que incluye una verdadera computadora interna para generar las imágenes que debe imprimir y manejar todo el complejo mecanismo de impresión y en el computador solo reside una “interfaz” para comunicar los datos a imprimir).

Conexión de los Controladores de E/S
Existen distintas variedades en la forma que un controlador se conecta con un computador, en particular teniendo en cuenta su lugar de residencia: si en el gabinete del periférico, si en el gabinete del computador o distribuido entre ambos. Veremos a continuación la representación esquemática de algunos de estos casos: 
1) El controlador de E/S está contenido en el gabinete del computador
	a) El controlador de E/S está conectado directamente al bus interno del sistema Este es el caso del controlador de video de un computador personal basado en bus ISA (Nota: en estos ejemplos estamos teniendo en cuenta que el bus ISA es prácticamente el bus interno con sus señales amplificadas).
	
	![[Pasted image 20221115164503.png]]

b) Se utiliza un adaptador de bus conectado directamente al bus interno del sistema Es el caso de un disco SCSI (Small Computer System Interface) en un computador con bus ISA. Estamos considerando que el hecho que el disco de un computador personal está contenido en el gabinete esto no modifica el hecho que también puede estar fuera, cuando se utiliza el estándar SCSI. En este caso la ubicación tiene que ver con aspectos mas vinculados a la comodidad y a la economía que a requerimientos técnicos.
![[Pasted image 20221115164603.png]]
c) Se utiliza un adaptador de bus conectado a un bus distinto del bus interno Es el caso de un disco SCSI (Small Computer System Interface) en un computador con bus PCI.
![[Pasted image 20221115164624.png]]

) El controlador de E/S está distribuido entre el gabinete del computador y el del periférico Es el caso del teclado de un computador personal, donde parte de la inteligencia reside en el propio teclado (posee un microcontrolador que realiza el barrido de las teclas para determinar si hay alguna presionada) y parte en la placa principal del computador (donde otro microcontrolador realiza algunas funciones de conversión de códigos y repetición de teclas).
![[Pasted image 20221115164651.png]]

## Acceso a los controladores de E/S

La comunicación de la CPU con los controladores de E/S se realiza a través de posiciones de memoria especiales de estos dispositivos, las que son accesibles también para la CPU. 
Existen dos tipos de arquitecturas de e/s respecto a la forma de acceso desde la cpu
1. La CPU dispone de un espacio de direcciones reservado para E/S, el cual es accedido por intrucciones dedicadas a este fin (in y out). Este es el caso de los procesadores INTEL
2. La CPU accee a los controladores de E/S como si se trataran de posiciones normales de memoria, utilizando para tales fines cualuquier instrucción que acceda a memoria. En general utilizado por microprocesadores RISC (SPARC, etc).
Estas memorias especiales de los controladores de E/S se llaman genéricamente **registros**.

Aún en el caso donde los registros son accedidos como memoria, no se comportan como memoria, pueden tener comportamientos tales como:

+ Solo lectura: El registro solo puede ser leído y si se escribe en él no se logra ningún efecto (luego de escribir lo que se lee no es lo que fue escrito)
+ Solo escritura: El registro solo puede ser escrito, al leer se obtiene un resultado inpredecible
+ Lectura/escritura independiente: En este caso se tienen dos registros diferentes, uno de solo lectura y otro de sólo escritura, accesibles en la misma dirección. Se podrá leer y escribir en esa direccion pero lo escrito allí será diferente a lo que luego se lea debido a que las posiciones de memoria accedidas en cada caso son separadas e independientes.
+ Lectura/ escritura normal: Estos registros se comportan como una posición de memoria normal, lo que se escribe puede ser leído más tarde.

Otra característica importante a tener en cuenta cuando se accede a E/S es quemuchas veces hay bits que no están definidos, por lo que al leerlos juntos en un byte o una palabra pueden tomar cualquier valor, con lo que la comparación del contenido del byte ó palabra con valores debe hacerse mediante el uso de máscaras (haciendo el AND bit a bit con un valor que tenga en uno aquellos bits que nos interesan, de forma que el resultado tenga únicamente en cuenta los bits que sí están definidos ó aquellos que nos interesan en cada momento). Algo similar ocurre al escribir, en algunos registros determinados bits que no están definidos deben, de todos modos, escribirse en un valor determinado (0 ó 1).

### Registros característicos

+ **Datos Entrada**: Contiene un dato destinado a la CPU, proveniente del perisférico, del propio controlador o de la línea de comunicaciones
+ **Datos Salida:** Contiene un dato proveniente de la CPU y destinado al perisférico, al propio controlador o a la linea de comunicaciones.
+ **Estado:** Contiene bits que indican el estado del controlador en sí mismo o del perisférico que controla (ej; si hau un dato en el registro de entrada, si esta libre el registro de salida, etc)
+ **Control:** Indican al controlador de e/s o al perisferico realizar alguna acción (ponerse en linea, reiniciarse, que lea del registro de salida, etc). En algunos controladores tambien se controlaban qué registros eran accesibles en cada momento en una direccion de E/S específica.