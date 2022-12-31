# Calculo de dominios.
#### From [[Lenguaje de consulta]].

En este caso el universo en vez de ser todas las tuplas  posibles, es la union de dominios de atributos.

Formulas son del tipo:
	$\{t_1,...,t_n|\phi\}$
Donde $t_i$ es una variable o cuna constatne, si es variable debe aparecer en $\phi$.

Ejemplo:
	$\{nom,dir|(\exists nf)(FABS(nf,nom,dir) \wedge VENTAS(nf,-,-)) \}$
(los atributos que no se necesitan se pueden poner como -).

