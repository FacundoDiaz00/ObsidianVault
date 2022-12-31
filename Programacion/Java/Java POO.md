# Java POO
### From: [[Java]].

## Definicion de una clase:
```java
public class Integer ectends Number implements Serializable{
	//class members go here.
}
```

## Modificadores:
- Modificador `abstract`: 
	- Implementacion incompleta, clase no instanciable.
- Modificador `final`:
	- La clase no podra/deberá ser extendida.

## Interfaces:
Las interfaces en Java existen explicitamente.

```java
interface Comparable{
	public int compareTo(Object o);
}

class MyClass implements Comparable{
	//...
}
```