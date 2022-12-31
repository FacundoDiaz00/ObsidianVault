# Practico 4: SQL
#### From [[SQL]]
## Ejercicio 1:

$a.I.$ obtener los números de los proveedores que proveen al proyecto número q o al proyecto número 2.
```sql
select distinct p.#prov 
from Poveen p
where p.#proy = 1 or p.#proy = 2
```

$a,II$ Obtener todos los datos de los productos de color "rojo"
```sql
select * 
from Proyectos prod
where prod.color = 'rojo'
```

$A.III$ Obtener el nombre de los proyectos de ciudades que comienzan con "M",
```sql
select distinct p.#proy 
from Proyectos p
where p.nomProy like %'M'
```

$A.IV$
```sql
select distinct p.categoria 
from Proveedores p
```

(en 1 y 3 no hace flata el distinct dado que los atributos seleccionados son determinantes)

$b.I$ Ternas donde un proveedor de la primera ciudad provee con el producto especificado a un proyecto de la segunda ciudad, las ciudades deben ser distintas.
```sql
select prov.ciudadProv, prvn.#prod, proy.ciudadProy
from Proveedores prov, Proyectos proy
where prvn.#prov = prov.#prov and prvn.#prod = proy.#prod and prvn.#proy = proy.#proy and prov.ciudadProv != proy.ciudadProy
```

Alternativamente:
```sql
select prov.ciudadProv, prvn.#prod, proy.ciudadProy
from Proveedores prov 
	natural join Proveen prvn
	natural join Proyectos
where prov.ciudadProv != proy.ciudadProy
```

$b,III$ Obtener todos los nombres de los proveedores que sólo proveen un producto y que prodceen dicho producto a al menos un proyecto.

```sql
select prov.nomProv
from Proovedores prov natural join Proveen prvn
where not exists(
	select *
	from Proveen prvn2
	where 
		prvn2.#prov = prvn.#prov and
		prvn2.#prod != prvn.#prod	
)
```

$b.IV$ Dar los nombres de los proveedores que proveen el mismo producto a todos los proyectos.
```sql
select prov.nomProv
from Proovedores prov natural
where not exists(
	select *
	from Proveen prvn
	where 
		prvn.#prov = prvn.#prov and
		exists(
			select *
			from Proveen prvn2
			where
				prvn2.#prov = prvn.#prov and
				prvn2.#prod <> prvn.#prod
				
		)
)
```

$c.I.$
Cantidad de productos provistos por cada proveedor
```sql
select count(distinct #prod)
from Proveen prov
group by #prov
)
```
Ojo, el distinct es necesario.

$c.II.$ Proyecto que es provisto por más proveedores

```sql
select *
from Proyectos p1
where not exists(
	select *
	from Proyectos p2
	where 
		(
		select count(distinct prov.#prov)
		from Proveen prov
		where prov.#proy = p1.proy
		) >
		(
		select count(distinct prov.#prov)
		from Proveen prov
		where prov.#proy = p2.proy 
		)

)	
```

Alternativamente:

```sql
select count(distinct #prov) c
from Proveen prov
group by #proy
order by c desc
limit 1
)
```

$c.III.$ Productos que son provistos a al menos 10 proyectos.
```sql
select *
from Productos prod
where
	select count(distinct #proy)
	from Proveen prov
	where prov.#prod = prod.#prod
) >= 10
```

## Ejercicio 2
$a.$ Cantidad de vuelos realizados por cada piloto.
Observar que la cantidad de vuelos es menor o igual a la cantidad de viajes
```sql
select count(distinct v.nroVuelo)
from Viajes v
group by v.nroPiloto
```

$b.$ Ciudad de destino a la que llegaron vuelos realizados por pilotos con más de 10 vuelos.
```sql
select distinct v.ciudadDestino
from Vuelos v natural join viajes
where select count(
	select(*)
	from Pilotos p
	where count(
		select count(distinct v.nroVuelo)
		from Viajes v
		group by v.nroPiloto
	) > 10
)
```

