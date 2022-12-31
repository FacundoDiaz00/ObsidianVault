# Codigos de Hamming:
### From: [[Codigos y errores]].

### Correccion de errores a partir de un codigo dado.

Sea un codigo: $b_3b_2b_1$, a los que se agregan los bits: $p_2p_1p_0$.

|     | b_3 | b_2 | b_1 | p_2 | b_0 | p_1 | P_0 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| s_2 | --- | --- | --- | --- | --- | --- | --- |
| s_1 | --- | --- | --- | --- | --- | --- |     |
| s_0 |     |     |     |     |     |     |     |
| 

Donde:
- $p_2 = b_3 \bigoplus b_2 \bigoplus b_1$
- $p_2 = b_3 \bigoplus b_2 \bigoplus b_0$
- $p_2 = b_3 \bigoplus b_1 \bigoplus b_0$

Y a su vez:
- $s_2 = p_2 \bigoplus b_3 \bigoplus b_2 \bigoplus b_1$
- $s_1 = p_1 \bigoplus b_3 \bigoplus b_2 \bigoplus b_0$
- $s_0 = p_0 \bigoplus b_3 \bigoplus b_1 \bigoplus b_0$

Si existen $b_i$ y $b_j$ con valor 1 o si todos los bits tienen valor 0 en el mismo codigo, entonces el valor de el $p$ de ese codigo es 0, y es claro que el valor de $s$ de este codigo tambien lo será.
Si existe un unico bit con valor 1, entonces $p$ tambien valdra 1, por lo que $s$ valdra 0.
Por lo tanto en cualquier caso donde s no valga 0 debe haber ocurrido un error.

Si falla el bit $b_2$ entonces $s_2 = 1$, $s_1 = 1$ y $s_0 = 0$. -> 110 = 6. 
Si falla el bit $b_0$ entonces $s_2= 0$, $s_1 = 1$ y $s_0 = 1$. -> 011 = 3.

Los numeros obtenidos son las posciciones (leyendo <-) del bit del codigo que falló.

## Construccion:
se concidera que x en la tabla puede representar un 1.
Las cruces de la tabla se pocisionan de forma que cada columna leida en binario representa al numero de su columna (las columnas se cuentan de forma decreciente [7, 6 ,5 ,...,0 ]).
Se observa que los bits $p$ se encuentra en las posiciones que son potencia de 2, esto se realiza para que en la tabla haya una sola x en la pocision de los $p$'s.
Luego $s_i$ es el $Xor$ de los $p$'s que TIENEN x en la fila correspondiente.

![[Pasted image 20220818013256.png]]