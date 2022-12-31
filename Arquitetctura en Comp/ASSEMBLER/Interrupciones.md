# Interrupciones.
#### From: [[Arquitetctura en Comp/Arqui]].
#### Notas: [[16-interrupciones-2012-4.3(1).pdf]]

## Introduccion:

```ad-quote
Una definición de interrupción puede ser: Una interrupción consiste en un mecanismo que provoca la alteración del orden lógico de ejecución de instrucciones como respuesta a un evento externo, generado por el hardware de entrada/salida en forma asincrónica al programa que está siendo ejecutado y fuera de su control. 
En forma alternativa se puede decir que: Una interrupción consiste en un mecanismo que le permite al hardware la invocación de una rutina fuera del control del programa que está siendo ejecutado.
```

Supongamos que el sistema quiere *esperar al input* de un usuario.
Una forma de diseño de este programa requiere un *loop esperando* por la aparicion de dicha entrada. 

A esta tecnica se le llama **polling**, el mecanismo de interrupciones es una alternativa al polling.

Si cada input requiere de 1000 instrucciones para ser procesadas, en el caso de que el procesador sea mucho mas rapido que los inputs realizados, mucho *tiempo del procesador se desperdicia en la espera (el bucle) entre pares de inputs*.

En el caso de que un dispositivo de entrada sea uno de almacenamiento de informacion.
Un disco magnetico tiene un tiempo de consulta que se puede medir en milisegundos. Tambien se gastan instrucciones a la espera de la lectura del disco. 

## Deteccion de interrupciones

**La deteccion del pedido de interrupcion se realiza al final del ciclo de instruccion. Por lo que la instruccion siempre termina antes de la interrupcion.**

**Los controladores de E/S** disponen de una *señal de salida* (habitualmente denominada INT ó INTR ó IRQ) que toma el valor "1" cuando el controlador interrumpe. 
Normalmente esa salida es el reflejo hardware de un *bit del registro de ESTADO*. El nivel actual (0 ó 1) de la señal INT del controlador de E/S puede leerse en un bit de dicho registro.
Este bit de *permanece en nivel alto* hasta que la rutina de atención de la interrupción realice *alguna operación* sobre los *registros del controlador de E/S* que satisfaga el pedido, con lo cual el controlador procederá a pasar ese bit (y su salida INT) a 0. 
Cuál es esa acción *dependerá del controlador* y, posiblemente, de la condición que provocó el pedido. Algunos pedidos de interrupción se satisfacen con la lectura del registro de estado, otros requieren de la lectura de algún registro adicional, otras requieren de la escritura de un registro, etc.

*En las CPUs también existe esta señal*, que recibe denominaciones similares (INT, IRQ, etc), pero que es de entrada. Esta entrada *es la que el hardware de la CPU consulta para determinar si hay algún pedido de interrupción* por parte de algún controlador de E/S.

### Deteccion por nivel
Cuando la forma de saber si hay un pedido de interrupcion pendiente es fijarse el valor de la entrada actual de la entrada

### Deteccion por flanco
Cuando la forma de saber si hay un pedido de interrupcion pendiente es detectar un cambio el valor de la entrada 

## Mecanismo de atencion

+ Termina instruccion en curso
+ Salva la dir de la proxima instruccion
	Distintas arquitecturas realizan esta actividad de diferentes formas.
	+ Podemos distinguir básicamente dos: - *utilizando un stack*. Esta vía es la habitual en las arquitecturas que implementan un stack por hardware.
	 - utilizando un registro. Esta vía es la habitual de las arquitecturas RISC, en particular la SPARC.
+ Identidica el disposivo (hardware) que interrumpe.
+ Obtiene direccion a la rutina de atencion a la interrupcion
	- la arquitectura Intel x86 utiliza un *identificador de 8 bits* del pedido de interrupción como *índice a una tabla (el vector de interrupciones)* que en cada entrada tiene la dirección absoluta de la rutina de interrupción asociada, formada por el segmento (valor a cargar en el registro de segmento de código) y el desplazamiento dentro del segmento (valor a cargar en el puntero de instrucción) de la dirección de memoria de la primer instrucción de la rutina de interrupción. 
	- La arquitectura SPARC utiliza también un *identificador de 8 bits para el pedido de interrupción,* el cuál multiplica por 16 antes de sumarle el valor contenido en un registro especial (el Trap Base Register, ó registro base de "traps", nombre que le da SPARC a las interrupciones) para formar la dirección a la cuál se va a pasar el control. De esta forma tenemos una especie de tabla que almacena las primeras 4 instrucciones (SPARC tiene instrucciones de largo fijo de 4 bytes) de cada rutina de interrupción.
+ Enmascara las interrupciones (siempre se lee el and entre la habilitacion de interrupciones y el pedido de interrupcion, si la habilitacion esta en 0 nunca se puede detectar una interrupcion)
+ Saltar a la rutina de atencion
## Vector de interrupciones.

Arreglo ubicado en el pimer Kbyte de memoria de 8086, tiene 256 posiciones, cada una de ellas de dos palabras (16+16 bytes) y son el puntero FAR a la rutina de interrupcion.

Notar que en el vector de interrupciones *utiliza el primer KByte de la memoria principal*, pero dado que se utiliza un identificador de 8 bits para determinar la direccion de la rutina de interrupción solo se podrán almacenar $2^8$ de estas.
Since *4 bytes are required to store the CS and IP* values for each interrupt service procedure, the table can hold the starting addresses for 256 interrupt service routines.

($2^{10}Byte \div 4Byte = 2^{8} = 256$)


### Contexto
Hay que evitar perder el contexto del programa que se estas ejecutando en el momento que se interrumpe el mismo, es por este motivo que se almacena,  por ejempo, la direccion de la siguiente isntruccion del programa, algunos procesadores guardan tambien las flags, etc

Si se interrumpe la rutina de atencion de una interrupcion *antes* de que la misma realize el guardado del contexto, es posible que se pierda esta informacion, por esto se enmascaran las interrupciones durante el mecanismo de instruccion antes de saltar a la rutina de atencion. Las interrupcioens en dicha rutina deben ser activadas intencionalmente por la misma

## Identificacion por Hardware.

### Líneas INT/IRQ independientes en la CPU

En este caso el propio CPU tiene *múltiples entradas INT* (numeradas, por ej: INT0, INT1, INT2, etc) y la idea es *conectar un controlador de E/S a cada* una de ellas. 

La identificación es entonces por hardware y directa: *el controlador que está pidiendo la interrupción es el que está conectado a la entrada INTn* donde se detecta la solicitud. En este caso hay una dirección de la rutina de servicio a la interrupción por cada línea de pedido disponible. 
En algunos casos, como en el ejemplo de la arquitectura SPARC, las *entradas de solicitud de interrupción están codificadas*. Esto quiere decir que el SPARC en vez de tener 16 entradas de solicitud independientes, tiene 4 entradas en las cuáles se presenta el código binario del pedido de interrupción. Esto exige la inclusión de un hardware de codificación externo a la CPU de forma de convertir las entradas de solicitud individual a las entradas codificadas de la CPU.

### INT/INTA

![[Pasted image 20221031205515.png]]

+ El CPU dispone de una única entrada de pedido de interrupción INT.
+ Se conectan en modalidad OR-cableado todos los pedidos de interrupción de los distintos controladores de E/S.
+ También dispone de una salida denominada *INTA* (Interrupt Acknowledge) que *le avisa al controlador de E/S que ha sido aceptado su solicitud de interrupción* y le indica con esa señal que coloque en el bus de datos su identificación. 
+ Cuando INTA vale 1, cada controlador (desde el primero) que no estan pidiendo interrupcion deben *replicar la señal*, esto hasta que se llegue al controlador que SI esta pidiendo interrupcion, este ultimo *corta la propagacion* y *coloca en el bus el identificador*.
+ La CPU entonces realiza una lectura del bus de datos y obtiene el identificador. Este procedimiento se extiende para el caso de múltiples controladores mediante el encadenamiento de las señales INTA
+ Existe una *prioridad* implícita en la forma de interconectar los controladores, los que estén *mas cerca de la CPU tendrán la posibilidad de ser atendidos antes* en caso de coincidir en el tiempo con un pedido de otro controlador mas lejano.


## Controlador de interrupciones

Es un controlador de E/S que maneja pedidios de interrupcion, acepta pedidos de interrupciones simples.

![[Pasted image 20221121142551.png]]

Se encarga de manejar las interrupciones simples de los controladores de E/S que no tienen INTA.

+ Cuando un controlador de E/S solicita una interrupción, *el controlador de interrupciones genera el pedido a la CPU* a través de la *señal INT*.
+ La CPU *cuando acepta la interrupción activa la señal INTA* y en ese momento es el controlador de interrupciones quién *coloca en el bus de datos la identificación que está asociada a la entrada IRQ* por la que llegó el pedido. 
+ El controlador de interrupciones es configurable y tiene registros en los cuales se puede almacenar cuál es la identificación que presentará para cada una de las líneas IRQ.

## Identificacion por Sotfware

Cuando *todos los controladores de E/S conecten su salida de pedido de interrupción en OR-Cableado* a la *única entrada INT* de la CPU. 
Aplica cuando hay múltiples controladores conectados en OR a la misma entrada de INT, sea ésta única o no.
En esta situación *la rutina de servicio de la interrupción debe tener una parte inicial* que consista en el recorrido de los distintos controladores de E/S, *leyendo los registros de estado* hasta encontrar aquél que tenga su bit de "pedido de interrupción" en "1".

### Identificacion por flanco

En caso de que un dispositivo haga un pedido de interrupcion al mismo tiempo que el otro dispositivo distinto esta siendo atendido, *dicho pedido va a ser "enmascarado" por la ejecucion*, dado que la entrada INT vale 1 a causa de la ejecucion pendiente.
Cuando dicha ejecucion termina, dado que el segundo dispositivo esta lanzando un pedido de interrupcion, pero su flanco no se detecto, *el valor de INT recibido por la CPU nunca deja de ser 1* por lo que todo el mecanismo de interrupciones queda *bloqueado*.

Para solucionar esto se debe *asegurar que la entrada int estubo en algun momento en 0*, para lo que es necesario recorrer todos los controladores de entrada/salida al menos dos veces.
Si en la primer recorrida encuentro un controlador haciendo un pedido de interrupcion, entonces lo atiendo. En caso contrario, es posible que durante la lectura de uno de los ultimos controladores, uno de los primeros se haya activado, por lo que es requerido verificar otra vez.
*Si las dos recorridas indican que no se realiza pedido de interrupcion significará que como mínimo, la primera recorrida habia seteado INT a 0* por lo que un pedido de interrupcion posterior hubiera causado un flanco, triggeriando una interrupcion.

### Habilitacion de interrupciones:
La cpu tiene la capacidad de aceptar o no los pedidos de interrupcion. Esta capacidad está implementada de dos maneras:

#### **Encmascaramiento**: (general)
En este caso la CPU inhibe la aceptacion de TODAS las solicitudes de interrupcion. Se realiza a traves del valor de un bit de máscara de interrupcion (IM = interrupt mask), (El = Enable interrupt) (ET = enable Traps) (dependiendo de la arquitectura). Normalmente perteneciente al registro de estado de la CPU (registro de flags o registro procesor status PS). La CPU par adeterminar si hay un pedido de interrupcion hace el AND de la señal de pedido interno de INT con el valor de este bit y utiliza este resultado para tomar la decision. Si el bit esta en 0 no existriá un pedido efectivo, en caso contrario se procesan los pedidos de interrupción.
Este bit cambia mediante instrucciones de enable y disable.
La Cpu pone automaticamente a 0 a este bit al invocar a la rutina de servicio de la interrupcion. Por ello una rutina de interrupcion comienza su ejecucion con las interrupciones deshabilitadas.
La instruccion que finaliza la rutina de interrupcion vuelve a recuperar el valor anterior del bit (1).
In todas las CPUs existe una entrada independiente de INT llamada NMI (Non maskabke interrupt) que trabaja de forma independiente de la mascara, cualquier pedido presentado por este medio es siempre procesado (se usa para falla de fuente de alimentacion, etc en la practica de los PC no se utilizan).

#### Deshabilitacion: (selectiva)
Se actua en cada controlador de E/S de forma individual.
Los controladore sde E/S tienen habitualmente un bit en su registro de *CONTROL* que actua como máscara para su salida de pedido de interrupción.
salida INT = bit INT registro de ESTADO AND bit MASK_INT registro de CONTROL
Notemos que el bit que refleja "pedido de interrupción pendiente" es de ESTADO, sigue reflejando si el controlador requiere de la intervención de la CPU.
El bit MASK_INT inihibe la generación de interrupciones por parte del controlador de E/S, Algunos contorladores disponen de otros bits que actuan a nivel diferencado, por ej, un controlador de  comunicaciones se pueden generar interrupciones por distintos motivos: recepción de un carácter, error en la línea de comunicaciones, carácter transmitido, cambio en las líneas de control de la comunicación, etc. y el controlador puede tener bits que inhiban en forma individual la generación de solicitudes de interrupción asociadas a cada condición.


## Interrupciones simultaneas 
El concepto de simultaneidad no implica que los pedidos de interrupción lleguen exactamente en el mismo instante del tiempo, sino que lleguen *durante el período entre una verificación y otra* por parte de la CPU, la cuál puede estar postergada en el tiempo si las *interrupciones están deshabilitadas*.

El mecanismo de prioridades puede adoptar distintas estrategias: prioridad fija, prioridad configurable o sin prioridad. 
+ Cuando la *prioridad es fija* siempre será atendida primero la solicitud que provenga de una *línea de pedido de mayor jerarquía*. Normalmente se utiliza la numeración de las entradas para fijar su prioridad. 
+ Cuando la prioridad es *configurable*, la misma se puede *cambiar en función de las condiciones del sistema en general*. 
+ Cuando el sistema es *sin prioridad* debe implementar un sistema de selección de la solicitud a atender que asegure la equitatividad en selección de las distintas entradas.

El mecanismo de prioridades puede estar implementado por *hardware* o por *software*. 
+ Cuando es por *hardware* se puede realizar 
	+ a nivel de la CPU (si tiene múltiples entradas de interrupción, ya sean directas o codificadas)
	+ A nivel del controlador de interrupciones.
+ Cuando es por *software* el mecanismo se implementa como un *algoritmo en la rutina de atención a la interrupción*,  mediante un apropiado *recorrido de los controladores* de E/S para *averiguar cuál fue el que interrumpió*, como ser: 
	- recorido **lineal**: siempre *comenzando por el mismo* y con un orden preestablecido (prioridad fija) 
	- recorrido **programable**: utilizando una *tabla* que establece el orden a seguir (prioridad configurable)
	- recorrido **"round-robin"**: comenzando cada vez en el *siguiente al último atendido*, en forma circular.

#### Interrupcion de Interrupcion.
La atencion o no de una interrupcion recibida durante la ejecucion de una rutina de interrupcion dependerá del esquema de jerarquias que tenga implementada la CPU y/o controlador de interrupciones.
Solo se aceptan interrupciones de un nivel igula o superior.
Para esto se mantiene en algun registro el "nivel actual de interrupcion"
Intel en el controlador de interrupciones contieen el registro ISR.
Sparc Lo hace a traves de los bits de IPL del registro PS (processor status, equivalente a flags)
 
## Rutinas de interrupcion

### Salvar el contexto.
La consideración fundamental es que las rutinas de interrupción deben preservar el contexto del programa interrumpido.

Se entiende por contexto de un programa a su estado completo, el cuál incluye  
todas sus variables y estructuras de memoria, incluyendo los registros de la CPU y registros especiales de la misma, en particular el registro de banderas o bits de condición (los bits Z, N, C y V).

#### Maquina no dedicada:
Multiples programas en ejecución con distintos propósitos, distintos programadores sin coordinación.
Maquinas programables.
NO se puede modificar ninguna parte del contexto.
En caso de que se tenga stack, es razonable guardarlo en el stack.

#### Maquina dedicada:
MAquina dedicada a una función especifica, todos los programas desarrollados por el msimo equipo o equipos coordinados.
Casos de controladores de artefactos especificos, ascensores, etc
En estos casos se puede evitar salvar el contexto.

### Estrategia de programacion:

#### Solo en main
Las rutinas de interrupcion solo hacen cosas minimas, como cambiar bandera para indicar que la interrupcion ocurrió, luego el main soluciona lo que se concidere necesario en base a esto.

#### Solo rutna de interrupcion:
El programa main habilita interrupciones y queda en loop eterno y TODA la logica queda en las rutinas de interrupcion. (mas dificil de debuggear en la vida real)

#### Hibrida:
Parte de la logica en main, parte en la rutina de interrupcion. (No recomendable para el curso)

Tener en cuenta en maquinas no dedicadas no se debe dejar en loop infinito.

Implmentar tecinicas de polling en sistemas de interrupciones:
+ Timer, que genera un interrupcion periódica y en la rutina de atencion se realiza la consulta al controlador de E/S. Tiene retarde de reaccion frente a un cambio en la E/S dado que se depende del período.
+ Se realiza el "polling" en el programa principal. asegura que la reaccion frente a un cambio en la E/S sea instantanea

## Operacion int

Las interrupciones son **por definicion** rutinas invocadas por un evento de *hardware*. En ese contexto una operacion INT no es realmente una interrupcion, la operacion int es una *invocacion a la rutina de interrupcion*
