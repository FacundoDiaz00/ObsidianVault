# Normalizacion
#### From [[BBDD]].
#### Notas: [[9-Normalizacion.pdf]].

A veces se obtienen dependencias a partir de unicamente la "letra" que describe la realidad. Como la definicion de $df$ exige una tabla, se asume que se estan imponiendo sobre la tabla universal.

Por lo tanto, las dependencias funcionales nos indican *que atributos deben pertenecer a la misma tabla*.

## Formas normales:
Es "una forma de armar tablas que da garantias"
Es util principalmente para optimizar tablas ya existentes.

Se desea que no surgan problemas de *tuplas erroneas* ni se pierdan *dfs* (ver [[Dependencias Funcionales.]] y [[Medidas de calidad]])

## Superclaves y dependencias
Dada una cave primaria es posible indicar que una segunda calve, tambien es clave (clave candidata)  mediante una dependencia de la forma:
	Sea $R=\{a,b,c,d,e,f\}$ donde $f$ es clave primaria.
	Se cumple $f\rightarrow a,b,c,d,e$
	Sea $a,b,c\rightarrow d,e,f$ 
En este caso $a,b,c$ es **superclave candidata**.
se puede expresar la informacion brindada por claves y superclaves en terminos de $dfs$ 

### Primera forma normal
Los dominios de los atributos solo deben incluir valores atomicos (no multivaluados ni compuestos)

### Atributo primo:
Un atributo es primo si es **miembro de alguna clave**.

### Dependencia total:
Una $df$ es **total** si la eliminacion de cualquier atributo de la izq hace que la $df$ deje de ser valida

### Dependencia parcial:
Una $df$ donde eliminando un atributo la dependencia se sigue cumpliendo.

## Segunda forma normal ($2NF$)

```ad-important
Un $er$ esta en $2NF$ si ningun atributo no primo $A$ de $R$ depende parcialmente de cualquier clave de $R$.
```

Para cada atribuo no primo, este no puede estar determinado por *una parte* de una clave, se deberia necesitar la totalidad de la clave para determinar cualquier atributo no primo).
No estar en segunda forma normal provoca redundancias de atributos (el mismo valor de atributo para muchas tuplas de la tabla.

```ad-note
Supongamos una tabla cuya calve esta compuesta por dos atributos $A,B$ , si existe otro atributo $C$ determinado *unicamente* por $A$, entonces todas las tuplas que compartan el valor de $A$ (notar que para un valor de $A$, habran varios valores de $B$ formando claves para distintas tuplas) compartiran también el valor de $C$, generando una redundancia
```

![[Pasted image 20220916044202.png]]
``` ad-note
(en esta caso (a) el nombre aparecería repetido cada vez que existan en la relacion dos tuplas con el mismo NSS)
```

Tambien es posible instanciar tuplas de empleado sin necesariamente cargar todos los atributos (evitamos atributos null).

### Dependencia transitiva.
Una $df$ es transitiva si existe un conjunto de atributos $Z$ que no es subset de una clave y se cumplen $X\rightarrow Z$ y $Z\rightarrow Y$

## Tercera forma normal:
```ad-important
Un $er$ esta en $3FN$ si esta en $2FN$ y ningun atributo no primo de $R$ depende transitivamente de una clave de $R$
```

Un $er$ $R$ esta en $3FN$ si, siempre que una $df$ $X\rightarrow A$ se cumple en $R$:
	+ $X$ es superclave de $R$
	o
	+ $A$ es atributo primo de $R$

Intuitivamente: si $X$ determina a $A$ entonces $X$ contiene a una clave o $A$ forma parte de la calve. Esto implica que los *unicos* atributos que determinan a otros (primos) son *superclaves*. Es la nocion de que **solo calves determinan a atributos no primos**

Obervar que esta forma permite que un *atributo primo* puede ser determinado por un atributo no primo.

![[Pasted image 20220917014015.png]]
En este ejempo (parte superiror del diagrama)  $NUMEROD\rightarrow NOMBRED$ y  $NUMEROD\rightarrow NSSGTED$ esta tabla *VIOLA* $3NF$ dado que la separacion provoca que los atributos de la derecha sean determinados por un atributo primo.

```ad-info
Obserbar que en la forma de arriba se tiene redundancia de datos ($NSSGTED$ queda repetido en cada tupla del mismo $NUMEROD$).
```


## Forma Normal de Boyce-Cod ($BCNF$)

Un $er$ esta en $BCNF$ si, siempre que una $df$ $X\rightarrow  A$ se cumple en $R$ entonces $X$ es una superclave de $R$.

Esta es una forma mas exigente que $3FN$.
Esta forma puede implicar que se pierdan $dfs$ aunque esto puede seguir siendo conveniente, es posible "anotarse" las dependencias que se pierden.
![[Pasted image 20220917020339.png]]

Para determinar que particion de la tabla es preferible son utilizados los [[Algoritmos de diseño]].


## Cuarta forma normal ([[Dependencias multivaluadas.]]): 


Un er esta en $4FN$ respecto a un conjunto de dependencias $F$ si esta en BCNF y para cada $dmv$ **no trivial** $X->>Y$ en $F+$, $X$ es superclave de $R$

![[Pasted image 20221016182118.png]]

![[Pasted image 20221016183259.png]]
Consejo: trabajar primero con las funcionales y después con las multivaluadas.