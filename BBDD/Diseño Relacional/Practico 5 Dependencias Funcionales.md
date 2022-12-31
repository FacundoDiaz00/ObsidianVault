# Practico 5 Dependencias funcionales.
#### From [[Dependencias Funcionales.]]

## Ejercicio 1:
![[Pasted image 20220918170027.png]]

La tabla $1.$ no satisface $F$ dado que en ambas filas poseen el valor de atributo $e_1$, y dado que en $F$ se cumple $E \rightarrow B$ entonces en la tabla deberia cumplirse que los valores de atributo de $B$ en ambas filas sean iguales.
La tabla $2.$ satisface $F$.
La tabla $3.$ no satisface $F$ dado que se deberia cumplir $B  \rightarrow D$ pero los valores de $D$ son distintos pese a tener igual valor de $B$  en ambas filas.
La tabla $4.$ satisface $F$.


## Ejercicio 2:

![[Pasted image 20220918170816.png]]
Parece valida.

![[Pasted image 20220918171057.png]]
Parece bien hecha la negacion, $\forall$ pasa a ser un $\not \exists$, y not $a \rightarrow b$ se niega como $a \land  \lnot b$ .

![[Pasted image 20220918171458.png]]
No entiendo a que se refiere con $t[XY]$ pero creo que quiere decir que los pares $X,Y$ son iugales para cualquier par de tuplas, esto es incorrecto dado que si los valores de $X$ son distintos, entonces los valores de $Y$ no necesitan ser iguales para que se mantenga la $df$

![[Pasted image 20220918171733.png]]
Nada impide que se repitan, lo unico necesario es que, si se repiten, determinen correctamente al valor de $Y$.

![[Pasted image 20220918171851.png]]
Correcta.

![[Pasted image 20220918172029.png]]
Falso, la correspondencia no es biyectiva dado que a un valor especifico de $Y$ le pueden corresponder varios valores de $X$ (aunque no al revez)

![[Pasted image 20220918172144.png]]
Correcta.

## Ejercicio 3

 ![[Pasted image 20220918204312.png]]
(cuantos valores distintos de $C$ hay tal que la tupla donde se encuetra $C$ comparte el valor de $A$ con alguna otra tupla y a la vez tiene distinto valor para $B$)

![[Pasted image 20220918204841.png]]

Significaria que no hay ninguna tupla tal que exista otra distinta con mismo atributo $A$ y distinto atributo $B$. 
Por el mismo criterio que en el ejercico $1.b$ la $df$ se cumple.

![[Pasted image 20220918205938.png]]
La segunda consulta cuenta los valores distintos de $A$ que es *MAYOR O IGUAL* a los posibles valores de $C$ (esto se debe a la $df$ impuesta en la letra, cada valor de $A$ debe corresponder con un *unico* valor de $C$,  a su vez cada valor de $C$ puede ocurrir relacionado a varios valores distintos de $A$, por esto se cumple la desigualdad)
Por esto el resultado de la consulta de la parte $b$ es mayor o igual a los posibles valores de $C$ que es a su vez mayor o igual al resultado de la consulta de la parte $a$.

## Ejercicio 7:
![[Pasted image 20220918212055.png]]

$a.$ $B \rightarrow C$, $C \rightarrow D \Rightarrow$ $B \rightarrow D$
$b.$ No, $E$ no aparrece en ningun lado izquierdo por lo que es imposible que determine algun atributo.
$c.$ $C \rightarrow E$, $C \rightarrow D$ $\Rightarrow C \rightarrow DE$
$d.$ No, $A$ requiere de $B$ para determinar algun atributo.
$e.$ No, $AH$ no determinan ningun atributo ni individualmente ni combinados.
$f.$  $C \rightarrow E$  $\Rightarrow CD \rightarrow E$
$g.$ No, $A$ requiere de $B$ para determinar algun atributo.

## Ejercicio 8
![[Pasted image 20220918214703.png]]
$a.$
![[BBDD P5 Ej8a]]

$b.$ Si, $EB{^+}$ y $EBC{^+}$ son superclaves.
$c.$ Si, $EB{^+}$ es clave, dado que si le saco algun elemento deja de ser superclave.
$d.$ En primer lugar observar que $B$ no aparece en ningun "lado derecho" por lo que necesariamente está en cualquier clave. Lo mismo ocurre con $E$, por lo tanto cualquier clave tiene tiene a $\{E,B\}$  como subconjunto como el mismo es clave, entonces cualquier otro candidato a calve lo contiene, por lo que este será superclave.
En conclucion $\{E,B\}$ es la única clave de $R$ segun $F$.

## Ejercicio 9:
![[Pasted image 20220919035218.png]]
Si $X \rightarrow A$ esta en $F{^+}$ entonces $A$ debe estar a la derecha en alguna $df$ de $F$. Por lo tanto debe existir tal $Y$.  

## Ejercicio 11
![[Pasted image 20220919040846.png]]

No pueden ser equivalentes dado que en $F_1$ no se cumple $C \rightarrow E$ el cual se cumple en $F_1$ .

![[Pasted image 20220919041529.png]]
No pueden ser equivalentes dado que en $F$ no se cumple $D \rightarrow C$.

![[Pasted image 20220919041824.png]]
Son equivalentes.

![[Pasted image 20220919042002.png]]
No pueden ser equivalentes dado que en $F$ no se cumple $A \rightarrow C$.

## Ejercicio 12.
![[Pasted image 20220919042503.png]]
$a.$
Pasos $1.$ y $2.$ del algoritmo no tienen efecto.
![[BBDD p5 Ej12a]]
Se eliminan las $dfs$ correspondientes al conjunto rojo o al conjunto nergrom, en cualquiera de los casos luego se elimina una restriccion cualquiera del conjunto que no fue eliminado.

![[Pasted image 20220919043459.png]]
Aplicando paso $1.$ el conjunto inicial no se ve modificado.
Aplicando el paso $2.$ 
- Se sustituye $AE \rightarrow D$ por $A \rightarrow D$.
- Se sustituye $DH \rightarrow C$ por  $D \rightarrow C$
- Se sustituye $CG \rightarrow B$ por $C \rightarrow B$
- Se sustituye $BI \rightarrow A$ por $B \rightarrow A$
![[BBDD P5Ej12b]]
Elimino flechas rojas O negras + una flecha adicional cualquiera.
