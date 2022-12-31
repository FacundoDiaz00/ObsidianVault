
#### From [[8086]].
#### Notas: [[cartillaIntel.pdf]]

### Comentarios:
Se indica el comienzo de un comentario mediante un ";".

### Cosntatnes:
Binarios, octales, hex, int, Strings
001101b, 664o,FE53h/0xFE53, 23, -120, "c" "hola mundo".

## Instrucciones.
Se escirben una de a renglon.
Cada instrucción teine un largo variable.

### Especificacion de una instruccion, ejemplo:
![[Pasted image 20220921045808.png]]
Se indica que banderas son afectadas por la ejecucion de la instruccion.

### Etiquetas.
Identifica una pocision dentro dle codigo.
Se utiliza para evitar tener que contar largo de instrucciones al realizar while's, for's, etc.
Formadas por letras y números.
``DoWhile:`` - isntruccion que define la etiqueta.
`DoWhile` - instruccion que referencia a la etiqueta (para ir hacia ella).

### Directivas.
Instrucciones al ensamblador.
EQU, asignarle un valor a una etiqueta. (escribir codigo mas lejible) ("la etiqueta que está a la izquierda la remplazo por lo que hay a la derecha")

DB, DW, DDW, reservan espacio para byte, word y double word.

PROC, da nombre a un procedimiento.

## Control de flujo:

+ ``CMP`` (compare), 
Las instrucciones de salto pueden ser *condicionales* o *incondicionales*.
+ ``JMP`` - incondicional.
+ ``JZ`` - Jump if zero
+ ...
+ ``JNLE`` - Jump if not less or equal (Con signo)
+ ...
## Variables.
Espacion de memoria con un nombre asignado.
En assembler son pocisiones de memoria con una etiqueta.
El tipo de variable a alto nivel se refleja en el tamaño que ocupan en memoria
No hay new o delete, son funciones de alto nivel.
Siempre tendrán una posicion de memoria asignada, puede ser en memoria, stack o registro.

### Malas practicas (que en assembler son necesarias):
+ while(true)
+ variables globales
+ goto/jmp

## Tipos básicos.

+ Char - 1 byte
+ short y unsigned short - 2 bytes.

### Punteros:
Los punteros pueden ser:
Dentro del msimo segmento (2bytes)
En otro segmento (2bytes desplazamiento y dos de segmento)
(siempre trabajamos dentro del segmento en el curso)


### Arrelgos:
#todo
- [x]  deje en min 34 pero hay cosas que no escuche bien.

Los elementos en un arreglo se guardan en pocisiones consecutivas de la memoria.

```ad-example
```
``` asm
MOV SI, 0
MOV AX, 0
MOV CX, 0
evaluar:
	CMP CX, 10
	JE fin
	ADD AX [BX+SI] ; BX contiene la pos del arr y SI el indice.
	ADD SI,2 ;Tamaño elem
	INC CX; Posición
	JMP evaluar
fin:
	...
```

## Manipular structs
Los campos del *struct* se almacenan consecutivamente de la misma forma que en el caso de array

```ad-example
```
``` asm
;si BX apunta al inicio
mov ax [BX]
mov ax, [BX+2]
...
```


## Procedimientos
Al llamar una funcion es posible pasar los **parámetros** mediante:
+ *Stack*, haciendo push a los parametros antes del llamada
+ Por *Registro*, cargando los datos en los registros antes de hacer el llamado

### Pasaje por stack
Se debe especificar la cantidad y el tamaño de  los parámetros.

```ad-example
```
``` asm
push dividendo
push divisor
call div_entera
pop cociente 
pop resto
```
``` asm
mov cx 1705
push cx
mov cx 6
push cx
call div_entera
pop ac
pop bx
```

Como la direccion de retorno se encontrará en el tope del stack al realizar el llamado de la funcion habra que acceder a los parametros "por debajo" del mismo.

### Manipulacion del stack con BP
Para poder manipular el stack y sus parámetros utilizaremos BP.
Se carga BP con un valor conocido (SP) que nos permita acceder a otras posiciones del stack.

```ad-important
BP utiliza como registro de segmento por defecto a SS
```


```ad-example
```
``` asm
push BP ; respaldo BP
mov BP,SP
SS:[BP] ;->BP anterior (respaldo)
SS:[BP+2] ;-> IP_retorno
SS:[BP+4] ;divisor
SS:[BP+6] ;dividendo
```
#todo 

- [x] Es lo msimo SS:[BP] que BP o [BP] ? dado que el segmento default de  BP es SS? creo que si, basandome en lo que se hace en este ej:
Notar que ``pop ax``, copia a ax el contendio de la posicion SS * 16+SP.

+ Cuando se hace un push, el valor a pushear se almacena en la poscicion $SS:[SP - 2]$, es decir dos memorias mas atras del lugar al que apunta SP. por lo tanto cada push se le resta 2 a SP.
+ Para recorrer el stack desde el BP hay que restar sucesivamente


```ad-example
```
``` asm
proc div-entera
	push BP ; respaldo BP
	push ax
	push dx
	push cx
	mov, dx,0;??? no seria XOR?
	mov AX, [BP+6]
	mov CX, [BP+4]
	div cx
	mov [BP+6] dx
	mov [BP+6] ax
	pop cx
	pop bx
	pop ax
	pop bp
	ret 
endproc
```

```ad-important
uando la *cantidad de parámetros* es *distinta* a la *cantridad de valores a retornar* es necesario acomodar el stack para que quede correctamente (ver diapos 8086), hacer esto puede requerir *MOVER EL SP*.
En caso de que se tengan más resultados que parámetros se deven reservar posiciones de stack al inicio de la rutina *Ver examen febrero 2016*
```

#todo 
- [x] Ver examen febrero 2016. 

### Llamadas FAR 
Hace push ademas de ``IP``, del ``CS``.
Se da un valor del nuevo segmento y del nuevo desplazamiento.

#todo 
- [x] Como funcionan las llamadas far exactemente?

### RET
Ret nos permite volver al punto anterior de ejecucion.

```ad-caution
RET asume que lo que se encuntra en el tupe del stack es la direccion de retonrno
```

#### Retorno far.
Realiza dos pop's, para recuperar del stack tanto el IP como el CS


## Contecto de ejecución
El *contexto* consiste en el *valor de los registros del CPU*.
Incluye *registros de datos* como de *estado*.
En assembly no tenemos asegurado de que luego de un llamado a funcion no se hayan modificado los valores de los registros. 
Se dice que **NO se conserva el contexto**.

Para preservar el contexto:
1. *Almacenar en el stack* el valor de todos los registros que se utilizan
2. *Ejecutar cuerpo* de la funcion
3. *Restaurar* desde el stack en *orden inverso* los registros
4. *Retornar* (el tope del stack debe contenr el valor del IP anterior)

## Rutinas Recursivas.
No toda funcion recursiva puede ejecutarse, esto se debe a que en llamadas near estamos limitados por la *cantidad de memoria del segmento*.

Nos interesa conocer su consumo máximo posible de stack.

```ad-example
```
```asm
FACT es una funcion que recive en AX un número positivo mayor o igual a 0 y devuelve en BX su factorial. NO preserva registros

fact proc
	cmp ax,0 ; comparo con 0
	je esCero
	dec ax
	call fact ;factorial de n-1
	inc ax
	mov cx ax; muevo n a cx
	mul bx ; multiplica por ax y guarda en ax
	mov bx ax
	mov ax cx muevo n a ax
	jmp fin
esCero:
	mov bx, 1;
fin:
	ret
fact endp
```
#### Consumo de stack:
	$Consumo(0) = 2bytes$
	$Consumo(n) = 2+Consumo(n-1)$
	$\Rightarrow$
	$Consumo(n) = 2*(n+1)$

Notar que esta version no guarda en contexto, lo cual aumentaria el consumo de stack, en las diapositivas hay un ejemplo del programa guardando el contexto.

```ad-important
Si luego del llamado recursivo dentro de la funcion se continuan ejecutando instrucciones, es probable que sea necesario guardar el contexto antes del llamado, para poder operar sin problemas luego de él.
```

## Info sobre Instrucciones especificas:

+ La lectura de datos mediante ``IN``, solo admite como puerto un imediato (de 0 a 255, 8 bits) o el contenido del registro ``DX``.
+ El ``XOR`` de un binario consigo mismo siempre retorna 0, utilizar esto es mas eficiente que hacer ``MOV``, hacer ``MOV`` en este contexto es eliminatorio.
+ `cmp word ptr [bp+4], 0`  El ensamblador debe poder determinar si la instruccion que queremos hacer es de byte o de word, se debe fijar en el tamaño de los operandos (1byte (ej registro cl), 1word (ej registro dx), indefinido (ej: cosntante 15 o *referencia a memoria indirecta*)) Assembly distingue 3 casos:
	+ Si conoce el tamaño de los dos operandos, corrobora que sean del mismo tamaño
	+ Si conoce solo uno de los dos, asume que el segundo es del mismo tamaño
	+ Si no conoce ninguno de los dos (`cmp word ptr [bp+4], 0`) hay que indicar el tamaño, word ptr y byte ptr indican el tamaño de la memoria (NO de la constante).
+ Cuando se utiliza `offset lista` se devuelve el desplazamiento de la variable (si defino 3 variables: a, b y c, offset c será 3, la varaible c estara contenida en la pos 3 del segmento ds) en caso de una lista retorna la ubicacion (respecto al segmento probablemente de datos) de la direccion de memoria del primer elemento de la lista.
+ Ja equiv jg,   jb equiv js
```

## Interrupciones:

Existen 2 instrucciones quetrabajan sobre el bit de enable interrupt

### CLI:
Clear interrupt, pone el bit a 0, por lo que deshabilita las interrupciones.
### STI
Start interrupt, pone el bit en 1 por lo que habilita las interrupciones.

### INT