[[Normalizacion]]
![[Pasted image 20221110212540.png]]

$\rho = \{(AB),(CDE),(EG),(BC)\}$

a.
$A \rightarrow C$
$B \rightarrow D$
$E \rightarrow G$
$C \rightarrow E$
$D \rightarrow G \rightarrow C$
$CD \rightarrow A$
Si el atributo de la columna esta en al tabla de la fila ponemos a_numCol y sino b_fila,columna, Las a son valores que no pueden cambiar, las b son "punteros" o "variables"

Luego utilizando las dnf cambio las b's por las a's correspondientes
|     | A     | B     | C     | D     | E     | G     |
| --- | ----- | ----- | ----- | ----- | ----- | ----- |
| AB  | a1    | a2    | b_1,3 | b_1,4 | b_1,5 | b_1,6 |
| CDE | b_2,1 | b_2,2 | a_3   | a_4   | a_5   | b_2,6 |
| EG  | b_3,1 | b_3,2 | b_3,3 | b_3,4 | a_5   | a_6   |
| BC  | b_4,1 | a_2   | b_4,3 | b_4,4 | b_4,5 | b_4,6 |
| 
En este caso en la columnaE mismo valor, dado que E->G deben compartir valor de G, se cambia b_2,6 por a_6
Lo mismo si comparten un valor y se determina que tienen el mismo B_i,j

|     | A     | B     | C     | D     | E     | G     |
| --- | ----- | ----- | ----- | ----- | ----- | ----- |
| AB  | a1    | a2    | b_1,3 | b_1,4 | b_1,5 | b_1,6 |
| CDE | b_2,1 | b_2,2 | a_3   | a_4   | a_5   | a_6 |
| EG  | b_3,1 | b_3,2 | a_3 | b_3,4 | a_5   | a_6   |
| BC  | b_4,1 | a_2   | b_4,3 | b_4,4 | b_4,5 | b_4,6 |

Luego

|     | A     | B     | C     | D     | E     | G     |
| --- | ----- | ----- | ----- | ----- | ----- | ----- |
| AB  | a1    | a2    | a3 | b_1,4 | a_5 | b_1,6 |
| CDE | b_2,1 | b_2,2 | a_3   | a_4   | a_5   | a_6 |
| EG  | b_3,1 | b_3,2 | a_3 | b_3,4 | a_5   | a_6   |
| BC  | a1 | a_2   | a3 | b_1,4 | a_5 | b_1,6 |

Si una fila tiene todos símbolos "a" entonces es con JSP en caso contrario no lo es.

$A \rightarrow C$
$B \rightarrow D$
$E \rightarrow G$
$C \rightarrow E$
$D \rightarrow G \rightarrow C$
$CD \rightarrow A$

