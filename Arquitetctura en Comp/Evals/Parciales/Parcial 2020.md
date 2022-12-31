# Parcial 2020

## Pregunta 1

Represente ⅓ (un tercio) en punto flotante de precisión simple (1,8,24) y acote el error en la  representación.
	$\frac{1}{3}=0,333333 \dots$
	Para convertir el numero a binario:
		$0,33333\cdot2 = 0,66666$
		$0,66666\cdot2 = 1,33332$
		$0,33332\cdot 2= 0,66664$
		...
		Por lo tanto la representacion en binario será: $0,0101010\dots$ 
		Se haya la representacion en IEEE
		$0,101010\dots = 1,01010\dots\times2^{-2}=1,01010\dots\times2^{127-125}$
	Luego la representacion será
| signo | exponente | mantisa                  |
| ----- | --------- | ------------------------ |
| 0     | 1111101  | 010101010101010101010101 |
El menor de los bits de la mantisa vale $2^{-23}$ pero ademas el exponente vale $2^{-2}$ por tanto el error en la representacion es menor a $2^{-25}$ .
En este caso la mantisa es periódica y con un  
patrón regular, por lo que es posible determinar de forma exacta el error en ⅓*$2^{-25}$


## Pregunta 2:
Utilizando la metodología del curso, diseñe el circuito para construir un flip-flop de  tipo T utilizando un flip-flop de tipo D.

![[ArquiParcial2020Ej2.excalidraw]]
## Problema 3.
![[examenFeb2020problema 3.excalidraw]]