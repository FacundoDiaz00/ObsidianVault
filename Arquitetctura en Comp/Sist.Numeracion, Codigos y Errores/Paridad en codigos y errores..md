# Paridad:
### From: [[Codigos y errores]]

## Consiste en:
## $n$ bits $+$ $1$ bit de paridad.
Este ultimo bit de paridad corresponde al $XOR$ de todos los bits (Paridad par).

Se observa que en el caso donde ocurre un error, se modifica la paridad por lo que es posible identificar que el error ocurrio.

El sistema es de distancia 2, se deben cambiar 2 bits minimo para producir un error sin que sea detectable (sin que se modifique la paridad).

De esta forma no es posible corregir errores.

## Paridad vertical:
$Sea$ $b_{n-1}b_{n-2}...b_0h_{m-1}$
 $b_{n-1}b_{n-2}...b_0h_{m-2}$
 $...$
 $b_{n-1}b_{n-2}...b_0h_{0}$
  $v_{n-1}v_{n-2}...v_0v_{0}$

Sistema con $m$ codigos de $n$ bits cada uno, donde $h$ es el bit de paridad calculado segun cada fila.
La ultima fila "completa la paridad de la columna".

En este caso si ocurre un error en el bit $b_i$ se observara que la paridad es incorrecta en la fila a la que pertenece el bit y a su vez la paridad e la columna será incorrecta, por lo que se podra localizar al bit victima del error.