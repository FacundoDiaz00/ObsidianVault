#### From: [[BBDD]]


Cuando se quiere que un atributo sea multivaluado, se requiere que exista una tupla en la tabla por cada valor distinto del atributo multivaluado 

Si se tienen 2 o más atributos que tienen **más** de un valor asociado con determinado objeto y estos atributos son independiantes entre si
(un estudiante que cursa un curso lo hace con todos los profesores de ese curso) se tendrán que repetir todos los valores de uno de los atributos con cada valor del otro atributo manteniando la misma referencia para los abjetos, para que las tuplas de la relación sigan siendo consistentes.

Def:
	una dmv $X->>Y$ sobre el er $R$ especifica la sigiente restriccion sobre cualquier relacion $r$ de $R$
	Si existen 2 tuplas $t_1$ y $t_2$ en $r$ tales que $t_{1}(X)= t_2(X)$  , entonces deberan existir 2 tuplas $t_{3},t_4$ en $r$ que cumplan:
	
	$t_{3}(X)= t_{4}(X)= t_{1}(X)= t_2(X)$
	$t_{3}(Y)= t_{1}(Y), t_{4}(Y)= t_2(Y)$
	$t_{3}[R-(XY)]= t_2[R-(XY)]$ y $t_4[R-(XY)]= t_1[R-(XY)]$ 
	Tienen el mismo valor en su atributo X.
	Cada una de las nuevas $t$'s  adoptan el valor de $Y$ de cada una de las viejas $t's$ 
	Cada una de las nuevas $t$'s tienen en el resto de sus atributos los mismos valores que la tupla de la que **NO** obtuvieron el valor de $Y$
	Esto es equivalente a crear nuevas tuplas con valores de Y intercambiados entre si 
	
Ej:
	sea la tabla $R(A,B,C)$ donde se cumple $A->>B$
	Si se tienen las tuplas:
		$a_1,b_1,c_1$ ($t_1$)
		$a_1,b_2,c_2$  ($t_2$)
	Entonces necesariamente se tienen que tener las tuplas:
		$a_1,b_1,c_2$  ($t_3$)
		$a_1,b_2,c_1$  ($t_4$)

Normalmente seria mejor no tener a B y C en la misma tabla.

Las dependencias *funcionales* son un caso particular de las dependencias *multivaluadas*.

### DMV Trivial

Una $dmv$ $X->>Y$ en $R$ es trivial si:
	$Y$ subset de $X$ ó
	$X \cup  Y=R$ 

#### Prop:
Siempre que se cumpla una dependencia funcional $X->Y$ tambien se cumple la multivaluada $X->>Y$. 


## Reglas:

![[Pasted image 20221016180651.png]]

## Cuarta forma Normal: [[Normalizacion]]

## Como encontrar dependencias multivaluadas:

Aparecen en atributos multivaluados: (telefono*)
En estos casos se agrega una tabla con el idenficador de la entidad y cada uno de los valores de dicho atributo.

Otras apariciones de dependencias multivaluadas normalmente provienen de traducciones patologicas de mer a relacional.

Lo mismo en el caso de las que provienen de restricciones no estructurales.

## Dependencias multivaluadas embebidas:

Si se cumple una multivaluada, se debería cumplir también la complementaria.

En el esquema R(Curso,Est,CPrev,AApp) se  
cumple la siguiente dependencia multivaluada  
embebida:  
+ Curso ->> Cprev | Est  
+ Esto significa que si en alguna descomposición  de R, aparece un esquema que tenga  exactamente todos los atributos de esa  dependencia (Curso, Cprev, Est), entonces esa dependencia se cumple en ese esquema.

![[Pasted image 20221120200815.png]]

