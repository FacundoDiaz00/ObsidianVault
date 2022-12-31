[[Java]]
1. Agregar carpeta de maven a PATH
Project object model es un xml con toda la info de config
Cua## Minimal POM[](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html#minimal-pom)

The minimum requirement for a POM are the following:

-   `project` root
-   `modelVersion` - should be set to 4.0.0
-   `groupId` - the id of the project's group.
-   `artifactId` - the id of the artifact (project)
-   `version` - the version of the artifact under the specified groupndo ejecutamos una task maven busca el pom 
One of these default values is the packaging type. Every Maven project has a packaging type. If it is not specified in the POM, then the default value "jar" would be used.

## Common problems

+ Multiple jars
+ Dependencies and versions
+ Project struct
+ Building, publishing and deploying


export M2_HOME = carpeta de instal
export PATH= carpeta de instal

## Compilation
	`mvn compile`
	`mvn package`
	java -cp coso

## Archetype

### Group ID, Artifact ID, version
Son los grupos, proyectos y versiones, identifican un artefacto en particular

### Packaging
	Especifica el tipo al que vas a compilar (JAR, WAR, ETC)

## Maeven build

### Build lifecycle:
1. Validate
2. Compile
3. tests
4.  package, genera el jar/war
5. install instala el paquete en un "repositorio" probablemente un repositorio de maven dentro del mismo dispositivo.
6. deploy

mvn compile
mvn test
mvn package
mvn install 

## Dependencies

Normalmente seria necesario descargar los jars y agregarlos al classpath
Con maeven se hace solo. 

Si importas cosas que no encuetra en el proyecto te tira error.
Hay que decirle que lo incluya en el pom
```
<dependencies>
	<dependency>
		<groupid>
		<artifactid>
		<versionid>
		<scope>
```
Maeven repository search te da los valores que tener que meter en el pom


## Web app con maeven

Tiene su propio pom of course

dentro del pom se incluyen las dependencias de javax.servlet, javax.servlet.jsp, junit 
