# Manupulacion de la representacion interna de datos en programas.
#### From [[Representacion interna de datos.]]


## Preguntas teoricas

### (a)
Nose a que se refiere con "conjunto de bits dentro de una tira"
...

## Ejercicio 1
### A)
```c
short a = 0xA87B;  // 1011 0111 1000 1010 ()
short b = 0x771C; // 0111 0111 0001 1100
short c = a | b; // 1111 0111 1001 1110
char d = c >> 4; //0000 1111 0111 1001 (lo "muevo" hacia >> por lo que pierdo data que se va hacia el "otro lado" de la ,) como es un char creo que trunco los bits menos significativos, deberia quedar algo asi como 0000 1111
```

### B)
```c
char a = 7; //   0000 0111 (BEL)
char b = 0xF3; // 1111 0011 = 243 (ó)
char c = 5; // 0000 0101 (ENQ)
short d = a << 12 | b << 4 | c

//a<<12 = 0000 0111 0000 0000 0000 (28672)

// b<< 4 = 1111 0011 0000 (3888) pero con offset de 4096 = -208

//a|b = 0000 0111 1111 0011 0000 ()

//|c 0000 0111 1111 0101

```

El caracter BEL hace ruido cuando lo imprimis.
```c
#include <stdio.h>
// un programa que hace ruido
int main()
{
    printf("Hello World\n");
    char a = 7; //   0000 0111 (BEL)
    char b = 0xF3; // 1111 0011 = 243 (ó)
    char c = 5; // 0000 0101 (ENQ)
    short d = a << 12 | b << 4 | c;
    printf("%s",&a);
    
    return 0;
}

```

```c
#include <stdio.h>

int main()
{
    printf("Hello World\n");
    char a = 7; //   0000 0111 (BEL)
    char b = 0xF3; // 1111 0011 = 243 (ó) el debugger me dice que esto es -13, offset de 256
    char c = 5; // 0000 0101 (ENQ)
    short d = a << 12 | b << 4 | c;
    short e = (a << 12) | (b << 4) | c;
    short f = a << 12;
    short g = b << 4;
    short h = f|g;
    short i = h|c;
    
    printf("%s",&a);
    printf("\n");
    printf("%s",&b);
    printf("\n");
    printf("%s",&c);
    printf("\n");
    printf("%hn",&d);
    
    return 0;
}
```

## Ej2

Algoritmo de suma de enteros de hasta 2 digitos.
Representado como entero sin signo empaquetado.

```c

short sumaBCD(char num1,char num2){
	// 1111 1111
	//aux1 y aux 2 seran las unidades de num1 y num2 respectivamente
	aux1 = num1 << 4;
	aux1 = aux1 >> 4;

	aux2 = num1 << 4;
	aux2 = num1 >> 4;

	res1 = aux1+aux2;

	resUnits = res1 << 4;
	resUnits = resUnits >>4;
	resDec = res1-resUnits;

	auxDec1 = num1>>4;
	auxDec2 = num2>>4:

	resDecFinal = auxDec1+auxDec2+resDec;
	return resDecFinal<<4 + resUnits;

}```