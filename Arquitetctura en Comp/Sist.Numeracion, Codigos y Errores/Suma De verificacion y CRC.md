# Suma de verificacion.
### From : [[Codigos y errores]].

Suma de verificacion consiste en sumar todos los codigos (interpretados como numeros) y al valor de esta suma modulo 2^n (si no se realiza este modulo el numero obtenido podria no ser representable con n bits) se lo envia como un nuevo codigo, luego sera posible saber si existio un error en el paquete.

Este sistema funciona aun cuando hay errores en codigos consecutivos (a diferencia de paridad).

# Codigo de Redundancia Ciclica:

$Sea$ $el$ $codigo:$ $001001001011011001100$ (o uno arbitrario).

Sea $M(x)$ el polinomio obtenido por los coeficiontes dados en el codigo.

Se plantea: $x^rM(x) = Q(x)G(x)+R(x)$

Luego existe un polinomio: $T(x) = x^rM(x) -R(x)$
Se observa que este polunomio es igual a $Q(x)R(x)$ .
$T(x)$ sera el utilizado para generar el codigo.
Se confirmara que el mensaje fue enviado sin errores si el codigopolinomio formado a partir del enviado (Coeficientes de $M(x)$) es divisible entre el obtendio por el codigo correspondiente a $T(x)$.
Se observa que el grado de $R$ es menor al de $G$ (el grado de $G$ es $r$) por lo que al transmitir $T$ se estaran transmitiendo los codigos de $M$ (sin alterar) en las primeras $r$ posiciones y luego los bits correspondientas a $R(x)$, a $R(x)$ se le llama $CRC$ (Codigo de redundancia ciclica).