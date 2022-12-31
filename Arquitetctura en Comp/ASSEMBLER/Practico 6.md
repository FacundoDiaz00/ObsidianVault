# Practico 6: Assembly
[[8086]] [[Ensamblador]]

## Ejercicio 2

Sea una CPU de 16 bits que tiene 8 registros de uso general de 16 bits y en la que las instrucciones se  
codifican en 16 bits. La CPU posee las siguientes instrucciones:

+ Para identificar cada uno de los 8 registros se requieren 3 bits, aparecen como maximo 3 registros en cada isntruccion por lo que en total seran 9 bits.
+ Se necesitan 4 bits para identificar cada una de las 16 instrucciones.
+ Los inmediatos son de 8 bits?

**ADD, SUB, AND, OR:**
| Instruccion | REG1  | REG2  | REG3  | zeros |
| ----------- | ----- | ----- | ----- | ----- |
| 4bits       | 3bits | 3bits | 3bits | 3bit  | 

**LOAD, STORE, NOT, CMP:**
| Instruccion | REG1  | REG2  | zeros |
| ----------- | ----- | ----- | ----- |
| 4bits       | 3bits | 3bits | 6bits |

**SETLO, SETHI:**
| Instruccion | Inmediato | REG  | zeros |
| ----------- | ----- | ----- | ----- |
| 4bits       | 8 bits | 3bits | 1 bits |

**SL, SR:**
| Instruccion | REG1  | INM   | REG2  | zeros |
| ----------- | ----- | ----- | ----- | ----- |
| 4bits       | 3bits | 4bits | 3bits | 2bit  |

**JZ, JN, JMP:**
| Instruccion | INM | zeros |
| ----------- | --- | ----- |
| 4bits       | 12  | 0bits |

## Ejercicio 3
La rutina ``BBinaria`` implementa el algoritmo de búsqueda binaria. Dada una palabra en la dirección de memoria 100h y una secuencia de 100 palabras ordenadas en memoria a partir de la dirección 101h  
hasta la dirección 165h, determina si la palabra pertenece a la secuencia, y en tal caso escribe en la posición 166h el valor 1, o en caso contrario escribe el valor 0.

``` c
void BBinaria () {  
	int inf, sup, medio, dato;  
	bool esta;  
	esta = false;  
	inf = 0x101;  
	sup = 0x165;  
	dato = memoria[0x100];  
	do {  
		medio = (inf + sup) / 2;  
		if (dato == (memoria[medio])) {  
			esta = true;  
		} else if (dato < memoria[medio]) {  
			sup = medio - 1;  
		} else {  
			inf = medio + 1;  
		}  
	} while (! (esta || (inf > sup)));  
	if (esta) {  
		memoria[0x166] = 1;  
	} else {  
		memoria[0x166] = 0;  
	}
}
```

``` assembly
SETHI 0x00 R1 //esta
SETLO 0x01 R1

SETHI 0x01 R2 //inf
SETLO 0x01 R2

SETHI 0x01 R3 //sup
SETLO 0x65 R3

SETHI 0x01 R4 //guardar la constante de direccion de dato
SETLO 0x00 R4

LOAD R4 R5 //dato en r5

ADD R2 R3 R5 //medio

SR R5 0x2 R5

CMP R4 [R5]
```
