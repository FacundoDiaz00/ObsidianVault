[[8086]], [[Ensamblador]]


## Ejercicio 2 $\star \star \star$ 

```ad-info
Dada la secuencia de naturales S(0), S(1), ..., S(N) definida por la relación:  
S(N) = S(N-1) + S(N-2). Siendo S(0)=0 y S(1)=1.  
```

A) Escribir en un lenguaje de alto nivel una función recursiva F(N) tal que F(N)=S(N). 

```c
int F(short int n){
	if(n == 0){
		return 0;
	}else if(n == 1){
		return 1;
	}else{
		return F(n-1) + F(n-2);
	}
}
```

B) Compilar la rutina en assembler 8086. El argumento se pasa en el registro AX y el valor de la  función se devuelve en el registro BX. 

```asm
.data  ; Segmento de datos

.code  ; Segmento de código
;AAAAAAAAAAAAAAAAAAAANDDDDDDDDDDDDAAAAAAAAAAAAAAAAAAAAAAA
	mov ax, 20
	call F
	end:
	jmp end
F proc
	cmp ax, 0
	je baseCero
	cmp ax, 1
	je baseUno
	
	push ax ;Guardo ax (contexto)

	dec ax ;preparo parametro
	call F ;llamo funcion

	push bx; guardo resultado

	dec ax ;preparo parametro
	call F
	pop cx; recupero el valor de bx que guardé
	add bx, cx
	pop ax
	ret
	baseCero:
		mov bx, 0
		ret
	baseUno:
		mov bx, 1
		ret
F endp

```



C) Calcular la cantidad de bytes mínima que debe tener el stack para que sea posible la ejecución  
de la función en el caso N=5.

$F(0) = 1$
$F(1) = 1$
$F(2) = 1+1+F(1)$
$F(n) = 2+ max(F(n-1), 1+F(n-2))$

$F(n) = 2 + F(n-1)$
#todo 
- [x] Preguntar como calcular cuanto espacio ocupa esto

## Ejercicio 3 $\star \star$  
Se considera la siguiente estructura de árbol binario, donde hijoIzq e hijoDer son los índices a los subárboles izquierdo y derecho respectivamente para un nodo dado.  
```c
struct Nodo {  
	short dato;  
	unsigned char hijoIzq, hijoDer;  
};  
Nodo arbol[256];  
```

El árbol tiene por lo menos un elemento. El valor 0 en hijoIzq o hijoDer significa que ese nodo no  tiene el sucesor correspondiente.  
A) Escribir en alto nivel una función recursiva que busca un entero en el árbol y devuelve true si  está y false en caso contrario. La función recibe como argumentos el entero a buscar y un índice  al árbol o subárbol donde buscar.

```c
bool isInTree(int num, unsigned char node){
	if(arbol[node].dato == num){
		return true;
	}else{
		return isInTree(num,arbol[node].hijoIzq) || isInTree(num,arbol[node].hijoDer)
	}
} 
```

B) Compilar la rutina en assembler 8086 sabiendo que en AX se recibe el entero y en BX el puntero  al árbol. El árbol se encuentra cargado en memoria a partir de la posición 0 del ES. El resultado  se devuelve en el registro CL (1 es TRUE y 0 es FALSE). Se deben conservar todos los demás registros.

```asm
.code  ; Segmento de código
	isInTree proc
		;ax recibe num,
		;bx recibe el puntero
		;Resultado en CL
		;Arbol en ES
		cmp ax, ES:[bx]
		je encontrado
		
		push bx
		;BUSQUEDA EN ARBOL IZQUIERDO
		cmp byte ptr es:[bx + 3], 0
		jne noEncontradoEnIzq
			
		mov bx, es:[bx + 3] ;Preparo parametro
		call isInTree
		cmp cl, 1
		je encontrado
		
		noEncontradoEnIzq:
		pop bx
		
		;BUSQUEDA EN ARBOL DERECHO
		cmp byte ptr es:[bx + 4], 0
		jne noEncontrado

		mov bx, es:[bx + 3] ;Preparo parametro
		call isInTree
		cmp cl, 1
		je encontrado
		
		noEncontrado:
			mov cl, 0
			ret

		encontrado:
			mov cl, 1
			ret

	isInTree endp
```


C) Calcular el tamaño mínimo que debe tener el stack para que la función pueda ser ejecutada en  todos los casos, cualquiera sea el tamaño del árbol.

## Ejercicio 4

Se considera un árbol binario cuyo nodo es definido de la siguiente manera (izquierdo y derecho son punteros a los dos subárboles del nodo):  
struct Nodo {  
Nodo* izquierdo;  
Nodo* derecho;  
short numero;  
};  
El árbol no tiene por qué estar balanceado. El valor NULL en cualquiera de los nodos (derecho o  izquierdo) significa que el nodo no tiene un sucesor por la correspondiente rama del árbol.  

A) Escribir en un lenguaje de alto nivel una función recursiva que calcula la profundidad del árbol  (largo máximo de caminos entre la raíz y un nodo)  
short profundidad(Nodo* arbol);  

B) Compilar la rutina en assembler 8086. El programa llamador hace la siguiente invocación:  
```
“PUSH segmento árbol”  
“PUSH offset árbol”  
CALL profundidad  
“POP profundidad”
```  

El resultado se devuelve en el stack y los argumentos deben retirarse del stack. Se deben  conservar todos los registros.  
*Nota: los punteros en este ejercicio son far y se representan en la estructura Nodo como 2  palabras (offset y segmento del puntero).*  

C) Calcular el tamaño del stack necesario en el peor caso para un árbol con N nodos.

Se asume que un node se almacena como:
| Forma de almacenar un nodo |     |
| -------------------------- | --- |
| Numero                     |     |
| segmento der               |     |
| offset der                 |     |
| Segmento izq               |     |
| offser izq                 |     |

![[Pasted image 20221108082217.png]]




