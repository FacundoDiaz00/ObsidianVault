# IEEE
### From: [[Representacion interna de datos.]]

Se expresa el numero mediante signo, exponente y mantisa.
De la forma: $(-1^s)\cdot1,F\cdot2^e$ 
Para el exponente se utiliza representacion de desplazamiento, para precision simple $d = 127$, para extendida $d = 1023$

Observar que el desplazamiento del exponente es tal que la mitad de los numeros sean positivos y la otra mitad negativos, por lo que si el exponente es de $e$ bits, el desplazamiento será $2^{e-1}-1$.  

```ad-example
$-15,625_{10} = -1111,101_2$ (transformar a binario)
$-1111,101 = -1,111101 \cdot 2^3$ (desplazar para llegar a la forma 1,...)
$\text{Utilizando 127 de corrimiento:}$
$e = 127 + 3 = 130 = 100000010$ (hayar el exponente que tendra la representacion).
$\text{Finalmente la representacion es:}$
$1|10000010|111101000\dots$
```

Notar que para cualquier

## Valores especiales del exponente:
| exponente       | mantisa    | Significado        |
| --------------- | ---------- | ------------------ |
| 0 < # < $2^e-1$ | Cualquiera | Numero Normalizado |
| 000...0         | 0          | CERO               |
| 000...0         | != 0       | DESNORMALIZADO     |
| 111...1         | 0          | INF                |
| 111...1         | != 0       | NaN                |

Notar que esto cambia cual es el mayor valor posible que un número en IEEE puede alcanzar (especificamente por que el eponente maximo esta reservado para INF y NaN)

Por lo que el número mas grande posible será:

| 1   | 111...0 | 1111111...1 |
| --- | ------- | ----------- |

![[Pasted image 20220925164512.png]]

## Numeros desnormalizados:
$(-1)^s\cdot2^{-d+1}\cdot0,m$
$d$ representa el desplazamiento del exponente.
![[Pasted image 20220922034331.png]]
![[Pasted image 20220922034406.png]]
