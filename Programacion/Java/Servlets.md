# Servlets
#### From [[Java]]

Progrmas java que se ejecuntan en un sevidor web.
El servlet recibe un patición del navegador y realiza su tarea.
- Generar una respuesta HTML
- Llamar a otros servlets
- Manejo de cookies y sesiones
- Enlace entre cliente y BBDD


Servlet envía data a jsp mediante atributos.
/home/facundod/Descargas/tpgr16/.metadata/.plugins/org.eclipse.wst.server.core/tmp0/wtpwebapps/ServidorWebDinamico/

getServletContext().getRealPath("/") + "/img" + (pedirle al dtusuario la imagen.path)

+ tomcat copia WEBAPP en sus archivos internos cuando se inicia el servidor, el webinfo sigue siendo "privado" dentro del condigo fuente.
				                        <%String imgpath =  pageContext.request.contextPath+"/img" + usr.getImg().getPath();%>
				                                    <a href="ConsultaDeUsuario?id=<%=usr.getNickname()%>&listar=false" class="btn btn-primary">Ver mas</a>
