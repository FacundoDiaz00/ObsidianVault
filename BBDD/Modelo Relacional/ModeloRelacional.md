# Modelo Relacional.
#### From [[BBDD]]


## Conceptos Generales:

### Dominio D:
Es un conjunto de valores atomicos.

### Esquema de relacion R(A1,...,An).
R es el nombre de la relacion.
A1...,An son los atributos con dominios D1,...,Dn.

### Una Relacion r(R):
Una unstancia de un esquema de realcion R.
Consiste en un conjunto de tuplas $r = <\{a_1,...,a_n\},\{b_1,...,b_n\},...>$ 
Tambien puede interpretarse como:
$r(R) \subset (D_1\times...\times D_n)$

### Tupla.
Unstancia de un esquema de relacion.

Ej:
	Esquema: $ESTUDIANTES(CI,nombre,dir)$
	Instancia: $\{<50538493, Juan,Maldonado 1121>, <...>\}$
Puede verse como un array o como una funcion.

### Superclave:

Dada una relacion $R$ un subconjunto de atributos es *supercalve* si contiene una clave. (no existen dos r(R) con superclaves iguales).

### Restricciones de Dominios.

#### Restricciones de dominios en los $D_i$.
Indica a que tipo pertenecen los valores de los atributos.
Pueen incluir subrangos o enumerados.

### Foreign Keys:

Dado R, un set de atributos X es una Fk de R que referencia a S si:
- Los atributos de X coinciden en el dominio con los de una clave Y de S 
	(Los atributos permiten identificar a la instancia de S)
- Los valores de X en tuplas de r(R) (para toda r) corresponden a valores de Y en la relacion s(S)
	(Los valores de X realmente referencian siempre a alguna instancia de S que existe).

### Integridad Referencial.

Se dice que existe una RI Referencial entre R y S, donde R referencia a S.

Es otra forma de decir que en R hay una foreing key sobre S

#### Ejemplo RI Referenciales.

+ Departamento.NSSGTE FK Empleado.NSS

(El num de seg social gte de un departamento es FK que hace referencia a el NSS de un empleado).

#### Validez de una BD

Todas las relaciones r deben satisfacer las RIs
Todas las instancias actuales de todas las relaciones delcaradas deben satisfacer todas las RIs.

## [[Operaciones en una base de datos.]]

## [[Lenguaje de consulta]]
