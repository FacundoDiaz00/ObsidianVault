[[8086]]
## Dudas:
 + en la version de c, como modelar lo de los puertos de salida.
 + en c, implementar clase pila o como?
 + se puede importar pila?
 + que significa: "programa en c que **modele** el problema ", es distinto a implementar?
 + **Que nombre ponerle a las variables en el programa de C, deben tener nombres del estilo AX,etc**
 + **Que deben hacer exactamente OUT y IN en el programa de C**
 + **DUMP y TOP deben enviar error si no hay elementos en la pila? o solo no imprimen nada**: DUMP SE CONCIDERA EXITOSA, no envia nada por el puerto de salida (foro)
 + **Que hacer en casos donde hay que enviar dos errores?? priorizar uno? enviar ambos?**
 + **Factorial en caso 0 o negativo**
 + Esta parte de la letra incluye el SWAP? asumo que si.
	 + "Cuando se desea realizar una operación binaria pero solamente se encuentra 1 elemento en la pila (el operando  derecho), además de dejar constancia en la bitácora se debe eliminar el elemento de la pila (quedará vacía)."

## TODOs
#todo
- [x] Agregar En C la impresion del codigo 0 y los operandos.
	Suponiendo que la pila está llena (tiene 31 operandos) y en la entrada te llega **1 n**  
	Entonces en la bitácora pones **0 1 n 4**, todo de acuerdo a lo que dice la letra:  
	**0 1 n** lo pones porque "Antes de procesar un comando se debe mandar el código 0 seguido del comando a procesar (incluyendo  
	los parámetros, una palabra por cada dato)"  
	
	**4** lo ponés porque  "Luego de procesar el comando se deberá mandar: el código 4 si la operación fallo por desbordamiento de la pila (ya hay 31 operandos) "
- [x] Saber si el log de "0" se hace dentro o fuera del switch
- [x] Saber si deberia definir mi stack sobre ES o DS.
- [x] CAMBIAR EN C LOG A SALIDA DONDE CORRESPONDA

## Data:

+ El maximo numero representable es 0xffff (16 bits).

+ **Todas las operaciones aritméticas** (incluyendo la multiplicación) son de **16 bits** y dejan como resultado en el tope de la pila los 16 bits menos significativos de la operación. (esto nos permite usar complemento a 2 conservando operaciones)

 + **Sobre codigo 0:**
	 El código 0 que aparece en la bitácora se pone por cada comando que se procesa, Se pone **0** Cmd Parametro 
	O sea, si el comando no tiene parámetros  **0 Cmd**
	Si el comando tiene 1 parámetro  **0 Cmd Parametro**
	Luego de procesar el comando se pone en el log el código asociado al resultado:
	En tu ejemplo, con la pila vacía y esta es la entrada **1 2 35 255** deberías poner en la bitácora:
	**0 1 2** (al recibir el comando 1 con parámetro 2)  
	**16** (luego de procesar ese comando)  
	**0 35** (al recibir el comando 35)  
	**2** (luego de procesar ese comando que es inválido)  
	**0 255** (al recibir el comando 255)  
	**16** (luego de procesar ese comando)
	Luego ya no se leería más la entrada ni se pondría nada más en la bitácora

+ La calculadora utiliza operandos enteros de 16 bits, tener en cuenta que el tamaño de palabra de 8086 es de 16 bits tambien, lo que significa que cada direccion de memoria almacena 16 bits (partes baja y alta)

+ ES parece iniciar en 0x00000, lo mismo ocurre con DS si no se le asigna algun valor a proposito.

+ Basic I/O y modificacion de puertos

```ad-example
```
```
;Entrada y salida basica
	mov dx, [ENTRADA]
	in AX, dx
	mov dx, [PUERTO_SALIDA_DEFECTO]
	out dx, ax
	
;modificacion del contenido de una variable
	mov [ENTRADA], 100h
	mov dx, [ENTRADA]
```



### Comprobaciones a realizar y dudas:
#todo 
- [x] Sobre la operacion SUMA: 
	Si. De la descripción del comando en la letra: "Calcula la suma de todos los elementos de la pila (borrando la pila) y deja el resultado en el tope de la pila. Si no hay elementos deja 0 en el tope."
- [x] Sobre PUERTOS DE LOG Y SALIDA:
	El puerto de log y el de salida podrían tener el mismo valor.  
	No deberían tener el mismo valor que el puerto de ENTRADA que es de solo lectura y no hay que hacer chequeos de que esto no ocurra (no se va a probar esa combinación)
- [x] IDIV Para divisiones(foro)
- [x] Cuando defino el puerto de entrada, si lo hago con dw funciona bien, sin embargo, si lo hago con db el contenido de la pos en memoria de ENTRADA no es la que se especifica en la definicion, porque?
- [x] Como declaro constantes? como declaro y donde doy valor a las variables de puertos?
- [x] Implemento Jump tables? o solamente lo dejo como cadena de if else?
- [x] En que contexto se usan registros como BP, SI, DI, etc
- [x] Como realizo el manejo de flags para evitar errores en los saltos? siempre que haga un cmp antes estoy seguro porque los actualizé?
- [x] Es usar add la mejor forma de sumar 2? es preferible inc 2 veces?
- [x] Es preferible *multiplicar el indice por 2* siempre o sumarle 2 en cada paso?
- [x] PILA dw dup(31) 0x0000???
- [x] Si en el codigo de c tengo un if que me permite *ENTRAR* al codigo que quiero ejecutar, puedo en assembly tener uno que me hace *SALIR* del codigo que no quiero ejecutar? algo asi como el complemento (ver caso num) Idem con **StackOverflow**
- [x] Que es mas efieciente para NEG, Multiplicar por -1 o invertir con algo de complemento a 1
- [x] Sum envia 8 cuando no hay elementos?
- [x] Personalidad de los registros.
- [x] Documentar las limitaciones de la funcion FACT Teste{ar por ej
- [x] Jump Tables a documentacion como posible mejora a futuro
- [x] Operaciones de dos operandos cuando no hay nada en pila lanzan 8? asumo que si, poner en documentacion
- [x] Documentar caso operacion que no este dentro de las opciones.
- [x] Documentar casos de prueba interesantes
- [x] Clear con nada en la pila
- [x] Se asume que Sum con un solo elemento funciona como la identidad
- [x] Orden de impresion en DUMP
- [x] documentar que nunca asumo nada sobre el estado de los registros
- [x] Comportamiento esperado de modulos de negativos, me estan dando negativos pero creo que se como se podria solucionar: -5%3 esta dando -2 que viene de que 3*-1 -2 = 3-2 = -5 pero deberia dar 1 dado que 3*-2 +1 = -6+1 = -5, por lo que **se solucionaria SUMANDO 3 A LO QUE DA EL RESULTADO**
- [x] capaz Documentar limitaciones de los shifteos (limite de tamaño de palabra)
- [x] URGENTE Arreglar DUMP y TOP
- [x] IMPORTANTE, saber donde estan por default los segmentos y que indica exactamente el Adress que se ve en ele exel de ArqSim
- [x] Preguntarle al man de los test por este caso
	56) 4097 = 1 0000 0000 0001
	
	ENTRADA: 1, 1, 1, 4097, 18, 4, 255
	
	LOG: 0, 1, 1, 16, 0, 1, 4097, 16, 0, 18, 16, 0, 4, 16, 0, 255, 16
	
	SALIDA: 0
- [x] IMPORTANTE: Test 3 esta mal y preguntaron en el eva
- [x] Sugerir en en informe utilizar interrupciones para la division entre 0
- [x] ver destacado de wsp sobre shifts
- [x] sum y fact tienen potencial de alcanzar valores mas altos del maximo representable
- [x] agregar que se eliminan los operandos de operaciones binarias
- [x] IMPORTANTE, LA OPERACION SUM SIN ELEMENTOS EN LA PILA DA 0,   La operacion Sum siempre termina con éxito.
- [x] En esa sección deben mencionar problemas que hayan encontrado durante el desarrollo del laboratorio y que ameriten ser contados, ya sea porque provcaron un cambio de diseño, porque les extendió el tiempo de desarrollo del laboratorio u alguna otra razón que les parezca meritoria. Deben usar su criterio para evaluar si algún problema encontrado merece estar en esta sección o no.



## Code repo

```ad-example
```
``` IntentoDeJumpTable
lista dw 17,18,19

.code  ; Segmento de código
	
	mov dx, [PUERTO_SALIDA_DEFECTO] ;Antes de procesar un comando, se debe mandar el código 0.
	mov ax, 0
	out dx, ax

	whileMain:

	mov dx, [ENTRADA]; Leo el puerto de entrada
	in AX, dx
	mov bx, word ptr [lista + 2]
	jmp bx
```

``` divisionVieja
Division:
		cmp word ptr [pilaTope], 0
		js OperacionSinElementos
		jbe OpBinariaElemsInsuficientes
		
		mov si, [pilaTope]
		mov bx, [pilaOps]
		mov ax, [bx + si] ;Envio a ax lo que hubiera en el tope
	
		add word ptr [pilaTope], -2
		mov si, [pilaTope]
		xor dx,dx
		cmp ax, 0 ; comparo, si NO se cumple ax >= 0 entonces se cambia el valor de dx
		jns dividir
		mov dx, 0xffff
		dividir:
		idiv word ptr [bx + si]
		mov [bx + si], ax
		jmp ComandoExitoso
```

``` mod-viejo
		cmp word ptr [pilaTope], 0
		js OperacionSinElementos
		jbe OpBinariaElemsInsuficientes
		
		mov si, [pilaTope]
		mov bx, [pilaOps]
		mov ax, [bx + si] ;Envio a ax lo que hubiera en el tope
	
		add word ptr [pilaTope], -2
		mov si, [pilaTope]
		xor dx,dx
		cmp ax, 0 ; comparo, si NO se cumple ax >= 0 entonces se cambia el valor de dx
		jns calcularMod
		mov dx, 0xffff
		calcularMod:
		idiv word ptr [bx + si]
		mov [bx + si], dx
		jmp ComandoExitoso
```

```dump_viejo
	Dump:
		xor si, si
		mov bx, [pilaOps]
		mov dx, [salidaPort]
		cmp word ptr [pilaTope], 0
		js fin ;si no hay elementos en la pila salgo directamente
		evaluar:
			cmp si, [pilaTope] ;Salgo del bucle cuando "si" es mayor al tope de la pila
			ja fin
			mov ax, [bx + si]
			out dx, ax
			add si,2 ;incremento pos en el arreglo
			jmp evaluar
		fin:
			jmp ComandoExitoso
```
## Documentacion

### Sobre los indices de la pila

indice 0 -pilaOps + 0 y pilaOps + 1 - 1 elemento
indice 1 - pilaOps + 2 y pilaOps + 3 - 2 elementos
indice 2 - pilaOps + 4 y pilaOps + 5 - 3 elementos
indice 3 - pilaOps + 6 y pilaOps + 7
...
indice 29 - pilaOps + 58 y pilaOps + 59
indice 30 - pilaOps + 60 y pilaOps + 61  - 31 elementos

Tambien se deberia poder implementar si siempre multiplico por dos el indice. nose que es mas eficiente

Por lo tanto cuando se tiene el TOPE EN 60 NO se pueden agregar mas operandos a la pila.

El tope del stack contiene el operando derecho de la operación binaria
https://eva.fing.edu.uy/mod/forum/discuss.php?d=253575

## Bibliografia

http://www.baskent.edu.tr/~tkaracay/etudio/ders/prg/pascal/PasHTM2/pas/lowlevel.html


Comando Parámetro Codigo Descripción  
Num Número 1 Agrega Numero a la pila  
Port Puerto 2 Setea el puerto de salida  
Log Puerto 3 Setea el puerto de la bitácora  
Top 4 Muestra el tope de la pila en el puerto de salida (no retira  
del la pila)  
Dump 5 Realiza un volcado de la pila en el puerto de salida (no  
retira de la pila)  
DUP 6 Duplica el tope de la pila  
SWAP 7 Intercambia tope de la pila con el elemento debajo  
Neg 8 Calcula el opuesto  
Fact 9 Calcula el factorial  
Sum 10 Calcula la suma de todos los elementos de la pila  
(borrando la pila) y deja el resultado en el tope de la pila.  
Si no hay elementos deja 0 en el tope.  
+,-,*,/,%,&,|,<<,>> 11 a 19 Realiza operación binaria  
Clear 254 Borra todo el contenido de la pila  
Halt 255 Detiene el procesamiento