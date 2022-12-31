[[Java]]
![[Pasted image 20221029173024.png]]
Motivado por la necesidad de comunicar sistemas implementandolos en distintas tecnologias.
Proveen una manera estandar de interpretar entre diferentes aplicaciones de software ejecuntando en distintas plataformas.

## Middleware
+ Es el siftware que permite gestionar partes de un sistema distribuido.
+ Permite interacciones de aplicacion entre distintos componentes de un abiente distribuido.

### Tipos de Middleware
+ Sockets (Bases de datos)
+ Message Oriented Middleware
+ Remote Procedure Call
+ *Web Services*
	+ SOAP: Simpre Object Acces Protocol (sobre HTTP)
	+ REST :Representational Acces Protocol (entdidades como recursos sobre la web)


## REST
+ Orientado a entidaddes
+ No tiene el overjead de soap, utiliza http directamente
+ Puede utilizar XML, Json, etc

## SOAP
+ orientado a operaciones
+ Protocolo sobre HTTP - librerias abstren la complejidad deluso real de SOAP
+ Precisa la utilizacion de XML.


### Elementos en la definicion de Servicios Web SOAP

+ XML Schema (XSD) para definir los tipos en los mansajes.
	Define la estructura de un documento XML incluyendo Tipos, atributos y relaciones válidas. 
+ WS Definition Languaje (WSDL) para especificar los WS.
	Define un servicio web, se tendra un documento de este tipo por cada ws/operacion de ws.
	Esta es la descripcion del servicio web, si una empresa o organizacion desea publicar en un servidor sus servicios para que cualquier interesado lo pueda consumir, debe publicar la direccion de este archivo (es un archivo xml), creo que alcanza con que permitan obtener este archivo de cualquier forma dado que el archivo es solamente un texto con la todal descripcion del servicio.
	Contiene la definicion de tipos (Asociada al XSM schema)
	Contiene una defincicion concreta del servicio, incluyendo mensajes de entrada y de salida.
+ Simple Object Acces Protocol para comunicacion.

![[Pasted image 20221029173050.png]]
![[Pasted image 20221029173350.png]]
![[Pasted image 20221029173953.png]]


### Cliente (Consumidor)
+ Entidad que desea consumir un servicio (hace invocaciones)

### Servidor (proveedor)
+ Entidad que brinda la insfra estructura para publicar un servicio y consumirlo

## Server Stub y Proxy

![[Pasted image 20221029184650.png]]

Server stub y proxy traducen los objetos java a mensajes soap (XML) y vice versa
### Server stub
+ Representa la logica del srv
+ Hace posible la publicacion
+ Existe en el entorno del servidor

### Proxy
+ Facilita al cliente el acceso al servicio
+ Encapsila la implementación asociada a dicho consumo
+ Construye objetos Java obtenidos del mensaje de respuesta para ser utilizados como si fueran locales a la aplicacion.

## WS import y interfaz con los servicios
Al intentar consumir un servicio uno debe enviar y recibir valores en un lenguaje neutral (xml) por lo tanto, para realizar una llamada a una funcion del ws se deben traducir los parametros de, por ejemplo java, a el formato utilizado por soap.
Por esto un traductor entre el lenguaje consumidor y soap debe ser agregado al proyecto consumidor. Este traductor se puede generar automaticametne por, por ejemplo, ws import (viene con java).


Un man en yt con tremendo uso de paint explicó todo mejor que el plantel docente de tprog en la historia del curso.
https://www.youtube.com/watch?v=C53G6R5EVys&list=PLqq-6Pq4lTTZTYpk_1DOowOGWJMIH5T39&index=2