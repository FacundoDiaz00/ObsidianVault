# FlipFlops
#### From [[Circuitos Secuenciales]]

## The LATCH
![[Pasted image 20220904011814.png]]

Circuito asigncronico basico.

Si esta todo apagado set prende Q o reset prende Qtecho
![[Pasted image 20220904012134.png]]
Pocicion de RESET, al mandar un pulso en set, se apaga Qtecho por lo que luego se prende Q

Si se envian pulso simltaneos el sistema no es prediecible, ocurre una *carrera*



## D Latch
![[Pasted image 20220904012514.png]]

(En pocision de reset)

Es un Latch que requiere Un *Enable* para poder cambiar su estado, una vez se esta en *Enable* si la corriente $D$ vale 0 el sistema automaticamente entra en *Reset*. Existe la posibilidad de que el sistema en enable reciba un pulso $D$ en este caso se seteara $Q$, si se desactiva el enable mientras $Q$ esta todavia seteado, el mismo permanecera Seteado hasta que se vuelva a activar el circuito.

## T FlipFlop 
https://www.youtube.com/watch?v=zq3GX75gejI

## EL JK FLIP FLOP

![[Pasted image 20220904013134.png]]

![[Pasted image 20220904015447.png]]

Funciona en flanco descendente del reloj.


Como Q y Qtecho son siempre distintas, las puertas and de J y K solo se pueden activar de a una a la vez. (cuando Q esta activa, es posible cumplir el and de K i viseversa)

Funciona como una especie de FlipFlop normal (k siendo el reset y J el set) pero en los casos de doble entrada funciona como un Tflipflop (invierte lo que estuviera)
![[Pasted image 20220925225912.png]]

