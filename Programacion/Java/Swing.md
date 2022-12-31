# Swing
#### From [[Java]].

## Jerarquia de componentes:
![[swinghierarchy.jpg]]

### Contenedores de alto nivel:

Los principales ejemplos son `JFrame` y `JDialog`.

#### JFrame:
	Ventana con titulo, borde y contenido.
#### JDialog:
	Sub ventana independiente.

Cada Top level conteiner contiene un content-pane que contendra a todos los componentes visibles.

Un top level conteiner puede opcionanalmente ontener una barra de menu que se mantiene fuera del content-pane.

### Componentes:
![[Pasted image 20220815142058.png]]
![[Pasted image 20220815142314.png]]

## Layauts:

Distribucion de elementos dentro de un disenio

### Layout manager:
Objeto que implementa la interfaz `LayoutManger`, determina posicion y tamanio de componetnes dentro de un contenedor.

![[Pasted image 20220815142612.png]]

## Eventos:

Un evento ocurre cada vez que el usuario interactua con componentes de la GUI

La funcion addActionListener toma como entrada un objeto de la clase ActionListener.A partir de este punto es posible determinar la implementacion de la funcion actionPerformed, que indica el comportamiento especifico del evento.
```java
JMenuItem menuSalir = new JMenuItem("Salir");
        menuSalir.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent arg0) {
                // Salgo de la aplicación
                frmGestionDeUsuarios.setVisible(false);
                frmGestionDeUsuarios.dispose();
            }
        });
```

Ejemplo de como abrir una ventana a partir de un evento.
```java
JMenuItem menuItemRegistrar = new JMenuItem("Registrar Usuario");
        menuItemRegistrar.addActionListener(new ActionListener() {
            public void actionPerformed(ActionEvent e) {
                // Muestro el InternalFrame para registrar un usuario
                creUsrInternalFrame.setVisible(true);
            }
        });
```