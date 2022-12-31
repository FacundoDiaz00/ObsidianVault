# Algebra de boole.
#### From: [[Arquitetctura en Comp/Arqui]].
#### Notas: [[Algebra de boole.pdf]]

## Axiomas del alegbra de bool:

1. Existe un conjunto $G$ de objetos sujetos a una Relacion De equivalencia "$=$" que satisface el *principio de sustitucion*.
2. a. Existe una regla $+$ tal que $a+b \in G$ 
    b. Existe una regla $\cdot$ tal que $a\cdot b \in G$
3. Neutros denotados por $0$ para $+$ y $1$ para $\cdot$
4. Ambas operaciones son conmutativas.
5. Distributivos.
	(a) $a+(b\cdot c) = (a+b)\cdot (a+c)$
	(b)$a\cdot(b+c) = a\cdot b + a\cdot c$
6. Para cada elemeto existe un complemento tal que $a*a = neutro*$
7. Existen por lo menos dos elementos $x,y$ en $G$ tal que $x <> y$
(La propiedad asociativa  a veces se toma como axioma pero es posible deducirla de los primeros 7).

## Modelo logico.
La intepretacion logica del modelo es:
	0 $\iff$  F.
	1 $\iff$ V.
	$+$ $\iff$ $or$
	$\cdot$ $\iff$ $and$
	$\neg$ $\iff$ $\overline{~}$
	

## Dualidad:
Cualquier postulado que se cumpla para $(+,0)$ tambien se cumple al cambiarlos por $(\cdot, 1)$. 
Por esto cada propiedad en esta Álgebra tiene una "dual" que también es cierta.

## Propiedades.
#### Idempotencia:
$a+a=a$.
$a\cdot a = a$

#### Neutros cruzados:
$a+1 = 1$
$a\cdot 0 = 0$

#### Complemento de complemento.
Para cada elmento de $G$ se cumple: $a = \overline{\overline{a}}$.

Para todo par se cumple:
	$a+ab=a$
	$a(a+b)=a$

Para todo par se cumple:
	$a+\overline{a}b=a+b$
	$a\cdot (\overline{a}+b) = a\cdot b$

#### Ley de morgan
Para todo par de elems de $G$ se cumple:
 
![[Pasted image 20220813174039.png]]

(no renderiza la barra bien latex).

![[Funciones booleanas]]

