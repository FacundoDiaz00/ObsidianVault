
[[Interrupciones]], [[Input-Ouput y buses]]

(a) Indique los valores visibles en los buses de direcciones, datos y control al realizar una operación de entrada salida, distinguiendo entre los casos de E/S aislada y E/S mapeada a memoria.

Direccion:
	Transporta informacion que permite *identificar las posiciones de memoria a leer ó escribir* y/o las entidades de E/S con las que se va a interactuar.

Datos:
	Transporta el valor del dato a escribir o leido

Control: 
	Transporta *señales que controlan el uso del bus* y la comunicacion sobre el mismo: [[Input-Ouput y buses]]

(b) Explique el propósito del controlador de interrupciones.

+ Transformar el pedido de interrupcion realizado por el dispositivo de entrada o salida en las señales correspondientes para que la computadora lo interprete como tal. NO EXACTAMENTE
+ RESPUESTA: En particular se utiliza en la arquitectura x86 como *forma de compatibilizar el mecanismo INT/INTA con controladores de E/S que no lo utilicen*. La idea es que un controlador de interrupciones posee múltiples líneas de entrada de solicitud INT (en el caso del 8259 de Intel se denominan IRQ) para la conexión de los pedidos de interrupción de los diferentes controladores de E/S. Tiene, a su vez, una única salida de pedido de interrupción INT con su correspondiente INTA para implementar el mecanismo de identificación por hardware.


(c) *Explique el mecanismo de INT/INTA* para manejar solicitudes de interrupciones y la *conexión Daisy Chain* utilizada ocasionalmente en conjunto con este mecanismo. ¿Existe alguna prioridad entre los dispositivos de E/S al utilizar esta conexión?

+ El mecanismo INT/INTA consiste en la utilizacion de señales para permitir al procesador identificar al dispositivo que interrrumpe. (No exactamente)
+ RESPUESTA: La idea es que el CPU dispone de una *única entrada de pedido* de interrupción INT, a la cuál se conectan en modalidad OR-cableado todos los pedidos de interrupción de los distintos controladores de E/S. También dispone de *una salida denominada INTA (Interrupt Acknowledge)* que le avisa al controlador de E/S que ha sido aceptado su solicitud de interrupción y *le indica con esa señal que coloque en el bus de datos su identificación*. La CPU entonces realiza una lectura del bus de datos y obtiene el identificador.

+ **Daisy Chain**: From wikipedia: In electrical and electronic engineering, a **daisy chain** is a wiring scheme in which multiple devices are wired together in sequence or in a ring, similar to a [garland of daisy flowers](https://en.wikipedia.org/wiki/Daisy_garland "Daisy garland"). Daisy chains may be used for power, analog signals, digital data, or a combination thereof. 
+ Este mecanismo dará prioridad a las interrupciones solicitadas por los dispositivos contectados de forma "*mas cercana*" a la cpu, esto se debe a que  el *primer* controlador de la cadena que tenga un pedido de interrupción pendiente procederá a *no continuar con la propagación* de la señal INTA hacia los restantes controladores y será él quien coloque en el bus de datos  su identificador.

(d) ¿Que significa que una maquina sea dedicada y que significa que no lo sea? ¿Que consecuencias tiene el tipo de maquina (dedicada/no dedicada) sobre la solución de un determinado problema?

+ Una maquina dedicada utiliza todos sus recursos para la resolucion de una tarea particular.
+ Una maquina no dedicada divide sus recursos para el uso de varios agentes interesados en ellos

**Dedicada** a una función específica y   todos los programas y rutinas que en ella se ejecutan están *desarrollados por el mismo equipo* de programadores o por equipos fuertemente coordinados.  En este caso los equipos de programadores pueden *establecer reglas* de uso de los recursos compartidos del sistema (típicamente los registros de la CPU) de forma que **se evite la necesidad de tener que salvarlos en la rutina de interrupción** e incluso puede existir  la necesidad de que la rutina de interrupción modifique alguna variable del programa interrumpido (típicamente el programa principal) de forma de alertarlo de alguna condición ocurrida en la E/S y comunicada por este mecanismo.

**No dedicada** existen múltiples programas en ejecución, con *distintos propósitos*, los cuáles han sido programados por *distintos equipos* de programadores, sin coordinación alguna. En este caso hay que respetar a rajatabla la regla que *la rutina de interrupción no puede modificar ninguna parte del contexto* del programa interrumpido y si requiere del uso de algún registro de la CPU (cosa harto probable) deberá previamente salvarlo.

(e) ¿Dónde está ubicado en memoria absoluta el vector de interrupciones del + 

+ 8086? ¿Es posible modificar esta posición?
En el primer kb de memoria en 8086, que yo sepa no se puede modificar

(f) ¿Que implica realizar la “instalación de la rutina” en Intel 8086?
Dentro del contexto de la estrategia de solo interrupciones:
toda la lógica se implementa en las rutinas de interrupción y el programa  
principal o bien está en loop infinito (máquina dedicada) o bien instala e inicializa las rutinas de interrupción y termina (máquina no dedicada).
- [x] Responde bien esta pregunta #todo
![[Pasted image 20221109010329.png]]


## Ejercicio 1 (en OpenFing)  $\star$

Se considera el *teclado* de una terminal de caracteres controlado por un microprocesador. El dispositivo es accesible mediante dos *registros de un byte ESTADO_TECLADO y DATO_TECLADO*, accesibles en direcciones de E/S de solo lectura. 
El hardware coloca el *valor 1* en el *bit más significativo de ESTADO_TECLADO* cuando hay un *carácter disponible*. Cuando se lee el carácter disponible en DATO_TECLADO, el hardware coloca el valor 0 en el bit más significativo de ESTADO_TECLADO.  

Escribir un procedimiento que lea los caracteres y los almacene en una lista de largo variable.

A priori pongo un while que haga el `IN` y actue en consecuencia

## Ejercicio 7 (en OpenFing)
+ Se desea controlar el escape de gas en una fábrica de recarga de garrafas. Por este motivo se instala un sistema de seguridad controlado por un procesador utilizado en forma dedicada. El sistema está formado por un *sensor de gas*, un *extractor* y una *válvula de corte*.
+ **El sensor** controla la concentración de gas en el ambiente. Es posible conocer si la concentración de gas es peligrosa o no consultando el registro de *E/S del sensor*.
+ **El extractor y la válvula** pueden controlarse manipulando el registro de lectura/escritura asociado a ellos. Una vez cerrada, la válvula sólo podrá abrirse manualmente.
+ El sistema debe *encender el extractor* toda vez que se detecte *escape de gas* (la concentración de gas es peligrosa) y *apagarlo* cuando el *escape culmina*. 
+ Si el escape persiste por *más de 30 segundos* se debe *cerrar la válvula* y apagar el extractor cuando el escape haya finalizado.  
+ El sensor está ubicado en la dirección de E/S *SENSOR*. EI bit 0 tiene el *valor 1* si la *concentración de gas es peligrosa* y el *valor 0* cuando *no lo es*. Los bits del 1 al 7 son reservados.  
+ El extractor y la válvula se controlan mediante la dirección de E/S *ACCESORIO*. El bit 0 se setea *a 1 para  encender el extractor* y a *0 para apagarlo*. *El bit 1 se setea a 0 para cerrar la válvula*. Los bits del 2 al 7 son reservados.  
+ Escribir todas las rutinas necesarias para implementar el sistema de seguridad en un lenguaje de alto nivel. Se dispone de un reloj externo que genera una interrupción cada 10 Hz que es atendida por la rutina tiempo().

![[Pasted image 20221109011720.png]]
#todo Nunca se preograman interrupciones en assembly en parciales?