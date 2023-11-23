## 5.1. Software Configuration Management.
En esta sección se detallan las decisiones y normas que posibilitarán que el equipo garantice la coherencia a lo largo de todo el ciclo de vida de desarrollo de nuestra solución.
### 5.1.1.	Software Development Environment Configuration.
En esta sección especificaremos y detallaremos las plataformas y software que usamos como equipo para la realización de nuestro startup.
- GitHub: En esta plataforma es donde crearemos nuestro repositorio donde realizaremos los avances de nuestro startup. Además, nos ayuda a tener un mejor control en el trabajo de equipo debido a que se puede visualizar el avance de cada integrante a través de los commits.
https://github.com/
- Git: Sistema de control de versiones más usado, es un requisito para poder realizar los commits en Github.
https://git-scm.com/downloads
- Discord: Es una aplicación de chat que permite crear grupos con las personas que elijas, además de ofrecer llamadas, videollamadas, subir archivos, etc. A través de la aplicación, logramos comunicarnos de manera exitosa para coordinar los puntos a realizar y solucionar dudas en grupo.
https://discord.com/download
 Visual Studio Code: Editor de código que nos permite trabajar con diversos lenguajes de programación, en este caso con los archivos de formato Markdown, además de permitirnos añadirle más funciones a través de las extensiones, de esta manera mejorar la experiencia de trabajo del grupo.
https://code.visualstudio.com/download
- Figma:
Es una herramienta esencial en nuestro conjunto de software para el desarrollo de nuestro startup. Esta plataforma nos permite colaborar de manera efectiva en el diseño y prototipado de nuestras aplicaciones y productos. Con Figma, podemos crear y compartir diseños en tiempo real, lo que facilita la revisión y la retroalimentación por parte de todo el equipo. Además, esta herramienta nos ayuda a mantener una coherencia visual en nuestros proyectos, lo que es fundamental para la experiencia del usuario. 
https://www.figma.com/
- UxPressia:
Es una plataforma en línea especializada en el mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps.
https://uxpressia.com/
- Webstorm: 
Es un entorno de desarrollo de JetBrains, una empresa especializada en software, orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para trabajar con lenguajes como HTML, CSS y JavaScript.
https://www.jetbrains.com/webstorm/
- Vue.js:
Es un framework open source de JavaScript, el cual nos permite construir interfaces de usuarios de una forma muy sencilla. En nuestro proyecto, utilizaremos Vue para la construcción del frontend.
https://es.vuejs.org/

### 5.1.2.	Source Code Management.
En esta sección presentamos los medios que usaremos para el seguimiento del desarrollo del código, usaremos la herramienta Github como plataforma y sistema de control de versiones.
Respositorio en GitHub para el Proyecto:
https://github.com/upc-coders/MapVet
- Main Branch:
  Es nuestro branch principal y la raiz de nuestras ramas, aquí se visualizará el estado del código fuente, que luego se redirigirá a production, y donde al finalizar las tareas de las otras ramas se incorporará al producto final.
- Develop Branch:
  En esta rama ubicamos el código fuente HEAD y podremos visualizar un estado con los últimos cambios realizados en el desarrollo. Todos los cambios que estén listos para publicarse serán fusionados al main Branch con una etiqueta del número de publicación. Además, cada cambio que realizaremos en esta rama volveran a fusionarse al main Branch como una nueva versión del producto.
- Capitulo 1 Branch:
  En esta rama se usa para subir y actualizar todos los archivos correspondientes al capítulo del documento, los cuales son: Startup Profile, Descripción de la Startup, Perfiles de integrantes del equipo, Solution Profile, Antecedentes y problemática, Lean UX Process, Lean UX Problem Statements, Lean UX Assumptions, Lean UX Hypothesis Statements, Lean UX Canvas, Segmentos objetivo.
- Capitulo 2 Branch:
  En esta rama se usa para subir y actualizar todos los archivos correspondientes al capítulo del documento, los cuales son: Competidores, Análisis competitivo, Estrategias y tácticas frente a competidores, Entrevistas, Diseño de entrevistas, Registro de entrevistas, Análisis de entrevistas, Needfinding, User Personas, User Task Matrix, User Journey Mapping, Empathy Mapping, As-is Scenario Mapping.
- Capitulo 3 Branch:
  En esta rama se usa para subir y actualizar todos los archivos correspondientes al capítulo del documento, los cuales son: To-Be Scenario Mapping, User Stories, Impact Mapping, Product Backlog.
- Capitulo 4 Branch:
  En esta rama se usa para subir y actualizar todos los archivos correspondientes al capítulo del documento, los cuales son: Style Guidelines, General Style Guidelines, Web Style Guidelines, Information Architecture, Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, Landing Page UI Design, Landing Page Wireframe, Landing Page Mock-up, Web Applications UX/UI Design, Web Applications Wireframes, Web Applications Wireflow Diagrams, Web Applications Mock-ups, Web Applications User Flow Diagrams, Web Applications Prototyping, Domain-Driven Software Architecture, Software Architecture Context Diagram, Software Architecture Container Diagrams, Software Architecture Components Diagrams, Software Object-Oriented Design, Class Diagrams, Class Dictionary, Database Design, Database Diagram.
- Capitulo 5 Branch:
  En esta rama se usa para subir y actualizar todos los archivos correspondientes al capítulo del documento, los cuales son: Software Configuration Management, Software Development Environment Configuration, Source Code Management, Source Code Style Guide & Conventions, Software Deployment Configuration, Landing Page, Services & Applications Implementation, Sprint n, Sprint Planning n, Sprint Backlog n, Development Evidence for Sprint Review, Testing Suite Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review, Team Collaboration Insights during Sprint, Validation Interviews, Diseño de Entrevistas, Registro de Entrevistas, Evaluaciones según heurísticas, Video About-the-Product.
- Feature Branches:
  En estas ramas las usaremos para desarrollar nuevas funciones para una próxima versión, estarán ramificadas desde el develop Branch y cuando se termine el desarrollo, será fusionado a la misma rama develop o se descartaría en caso la función no tenga buenos resultados.

### Conventional Commits:
Es una convención ligera sobre los mensajes de confirmación. Nos proporciona un conjunto de reglas las cuales debemos seguir para poder crear el historial de commits , lo que nos facilita la escritura de herramientas automatizadas. Los commits tienen diversos elementos estructurales para comunicar los diversos cambios realizados.
- fix: usamos este commit del tipo fix cuando se arregla un bug que afecta al usuario.
- feat: usamos este commit del tipo feat cuando se agrega una nueva característica para el usuario.
- perf: Cambios que mejoran el rendimiento del sitio.
- build: Para los cambios en el sistema de build.
- ci: Para los cambios en la integración continua.
- docs: Para cambios en la documentación.
- refactor: Cuando se realiza una refactorización del código como cambios de nombre de variables o funciones.
- style: Para los cambios de formato, tabulaciones, espacios o puntos y coma, etc;
- test: Cuando se añade tests o refactoriza uno existente.

### 5.1.3.	Source Code Style Guide & Conventions.
**Convenciones que se usarán para el desarrollo del Landing Page:**
Para el desarrollo del Landing Page se usarán las siguientes nomenclaturas.
-	Usaremos nomenclatura en inglés
-	Declaración del tipo de documento
     En nuestro archivo index.html en la primera línea de código colocaremos la instrucción <!DODCTYPE html>
-	Atributo Lang
     Con este atributo podemos permitir que los motores de busqueda puedan identificar y configurar nuestro idioma.
-	Implementaremos la etiqueta meta data
     Esta nos servirá para que en nuestro documento HTML, pueda proporcionar información codificada a navegadores y motores de búsqueda acerca de nuestra página web
     Para las convenciones de nomenclatura en CSS:
-	En nuestra codificación de nuestro proyecto, usaremos las minusculas para nombrar estos archivos con el fin de no tener conflictos con los nombres de nuestros archivos html.
-	Se evitará el uso de las tildes para los nombres de estas.
-	Se abreviarán los nombres con el fin de tener una mejor practicidad.
-	Se usará nomenclatura en inglés.
     Convenciones para la nomenclatura en JavaScript:
-	Paquetes
     El prefijo del nombre en un paquete se escribirá con el código ASCII.
     El nombre del paquete será escrito en minúsculas y debe ser uno de los nombres de dominio de alto nivel.
     com.sun.eng
-	Clases
     Usaremos palabras simples.
     En caso sea una sola palabra todo irá en minuscula, Por otro lado, si el nombre fuese una frase compuesta usaremos el tipo 'StudlyCaps'; es decir, cada inicio de una palabra del nombre compuesto va en mayúscula. Así, diferenciarlo de otras estructuras.
     Usaremos palabras completas, sin abreviatura.
     class PetOwner;
-	Variables
     Usaremos el camelCase para nombrar a nuestras variables. Además se evitará el uso de los caracteres especiales con el fin de evitar posibles errores en nuestro proyecto.
-	Constantes
     Seran nombradas en mayúsculas. En caso el nombre sea compuesto se usará un guion abajo como separador (_) .

### 5.1.4.	Software Deployment Configuration.
Para el despliegue de nuestra landing page usamos GitHub donde primero realizamos la creación de nuestro repositorio donde se desarrollará el código de nuestra landing page

![Repository Created](https://i.ibb.co/dfcRwbQ/Repository-Landing.png)

Una vez creado nuestro repositorio, nos repartimos las distintas user stories para el desarrollo de nuestra landing page y creamos las ramas necesarias para que cada integrante pueda trabajar sin complicaciones.

![Branches](https://i.ibb.co/7RrX5KC/Branches.png)

En el apartado de build and deployment selecciónamos la rama que queremos que se despliegue, en nuestro caso sería la rama develop, en la cual se realizan todos los cambios.

![Github pages used](https://i.ibb.co/V9jWbBp/Github-Pages-Config.png)

Le damos a guardar y empezaría el despliegue de nuestro landing en Github Pages, nos generará un link con el cual podemos acceder a nuestro landing page.

![Landing Page image](https://i.ibb.co/tZhpqC7/Landing-Page.png)

Link de la landing page: https://upc-coders.github.io/MapVet-LandingPage/

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
En esta sección, se detalla el proceso completo de implementación y despliegue de la Landing Page. Se aborda de manera grupal, detallando planificación del avance desde la concepción del Product Backlog hasta la puesta en producción de este componente en nuestro proyecto.
### 5.2.1.1. Sprint Planning 1
En el Sprint Planning 1 se planificó para la elaboración de la landing page del proyecto. Mediante una reunión grupal se determinaron y acordaron distintos puntos para su elaboración

|             Sprint #             |                                                                                                                               Sprint 1                                                                                                                                | 
|:--------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  **Sprint Planning Background**  |                                                                                                                                                                                                                                                                       |
|               Date               |                                                                                                                              	2023-09-22                                                                                                                              |
|               Time               |                                                                                                                               08:00 PM	                                                                                                                               |
|             Location             |                                                                                                                          	Virtual (Discord)                                                                                                                           |
|           Prepared By            |                                                                                                                 	 Juliana Yauricasa, Daniel Valverde                                                                                                                  |
|            Attendees             |                                                 Renato German Reyes Valenzuela / Juan Jesús Calisaya Sánchez / Josue Daniel Valverde Lopez / Sebastian Andre Ramirez Mendez / Juliana Yauricasa Seguil              	                                                 |
|    Sprint 1 - Review Summary     | Se asignaron tasks para los integrantes del grupo para la elaboración de la landing page. Se acordó que la fecha de entrega de los tasks será hasta el 23 de septiembre de 2023                                                                                     	 |
| Sprint 1 - Retrospective Summary |                           Un miembro del grupo consultó la posibilidad de ampliar la fecha de entrega de las tareas asignadas.                                                                                                            	                           |
|  **Sprint Goal & User Stories**  |                                                                                                                                                                                                                                                                       |
|          Sprint 1 Goal           |                                         Despliegue de la landing page en su totalidad, en un lapso de 3 días                                                                                                               	                                          |
|        Sprint 1 Velocity         |                                                                                             30                                                                         	                                                                                              |
|       Sum of Story Points        |                                                                                                         27                                                  	                                                                                                         |

### 5.2.1.2. Sprint Backlog 1
El objetivo principal del Sprint 1 es lograr la implementación de la landing page del proyecto, a continuación se muestra una tabla en la cual se presentan las historias de usuario y las tareas que se desprenden de cada una. Se destaca en importancia la asignación y el estado de la tarea.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>Description</strong></td>
    <td align="center"> <strong>Estimation (Hours)</strong></td>
    <td align="center"> <strong>Assigned To</strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="2" align="center"> ID </td>
    <td rowspan="2" align="center"> US21: Ver Preguntas Frecuentes (FAQ) </td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir preguntas</td>
    <td align="justify"> Se añadirán las preguntas frecuentes en cards</td>
    <td align="center"> 1 </td>
    <td align="center"> Sebastian Ramirez </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Redirección de secciones </td>
    <td align="center"> Agregar un navbar para redirigirse otras secciones de la landing page</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td rowspan="2" align="center"> ID </td>
    <td rowspan="2" align="center"> US 19: Ver el perfil de la mascota</td>
    <td align="center"> TA01 </td>
    <td align="center"> Se añadirá información de las mascotas </td>
    <td align="center"> Dado que la mascota cuenta con su información registrada, se mostrará su perfil</td>
    <td align="center"> 2</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Agregar estilos</td>
    <td align="center"> Se usará css para mostrar la información en una tabla </td>
    <td align="center"> 1</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center"> Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US 17: Hacer una cita</td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir campos de información</td>
    <td align="center"> Se añaden los campos para que sean completados por el usuario y confirme con el boton "Nueva Cita" </td>
    <td align="center"> 3</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Seleccionar veterinaria</td>
    <td align="center"> Se mostrará la información final de los detalles de la cita y un botón "Reservar" para confirmar la cita</td>
    <td align="center"> 2</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Muestra de las citas registradas </td>
    <td align="center"> Se muestran en cards las citas registradas con su respectiva información </td>
    <td align="center"> 2</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center"> Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center">  US 16: Apartado de recomendaciones </td>
    <td align="center"> TA01 </td>
    <td align="center"> Redirección de secciones </td>
    <td align="center"> Agregar un navbar para redirigirse otras secciones de la landing page</td>
    <td align="center"> 1</td>
    <td align="center"> Renato Reyes</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Muestra de veterinarias recomendadas </td>
    <td align="center"> Se agrega una foto de la veterinaria recomendada en la cual se puede hacer click para mostrar más detalles </td>
    <td align="center"> 2</td>
    <td align="center"> Renato Reyes</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Opciones disponibles</td>
    <td align="center"> Se muestran opciones de los servicios que ofrece la veterinaria para poder elegir</td>
    <td align="center"> 3</td>
    <td align="center"> Renato Reyes</td>
    <td align="center"> Done</td>
  </tr>

</table>

### 5.2.1.3. Development Evidence for Sprint Review.

|                       Repository                       |                    Branch                     |                                                      Commit Id                                                       |                                    Commit Message                                    | Commit Message Body |    Committed on (Date)    |
|:------------------------------------------------------:|:---------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:-------------------:|:-------------------------:|
| https://github.com/upc-coders/MapVet-LandingPage-Final |             feature/appoinment 	              |                                    cd2db005aec1211ae32c0a4e05a83b8c3836b895  	 	                                     |                     feat(appointment): added appointment    	 	                      |    ---      	 	     |   26/09/2023        	 	   |
|                                                        |         feature/appoinment         	          |                           e376c303c755645279d5d020bded67dd117e2c88                     	 	                           |         feat(bookappointment): added bookappointment.                    	 	         |    ---       	 	    |  26/09/2023         	 	   |
|                                                        |       feature/appoinment             	        |                           bcdfda415ef4d64ce709b4d6107042ccad986700                     	 	                           |         feat(newappointment): added bookappointment.                    	 	          |   ---        	 	    |  26/09/2023         	 	   |
|                                                        |         feature/login               	         |                      6f099c2eb153ee29d25fcd0bde3514faf186095d                              	 	                       |              feat(login): add login                                	 	               | ---             	 	 |  26/09/2023         	 	   |
|                                                        |          feature/login             	          |                      beef323fb9ee15c34760a63989c3f9beda3c4711                              	 	                       |        feat(userregister): add userregister                               	 	        |   ---        	 	    |  26/09/2023          	 	  |
|                                                        |    feature/recommendations               	    |                     548637f9a0aa62b5c9066ba51e2e1bdc7b9f59d2                                 	 	                     | feat(reviews): added reviews                                                     	 	 |   ---         	 	   |  26/09/2023          	 	  |
|                                                        | feature/recommendations                     	 |                    5ee4dcda633acce7419355da1d480097ce27da74                                   	 	                    |   feat(infoveterinary): added infoveterinary                                  	 	    |    ---       	 	    | 26/09/2023            	 	 |
|                                                        |  feature/recommendations                   	  |                    971651832eee4a9ad313555898c78b6cfa58d9be                                  	 	                     |         feat(mainmenu): added mainmenu                                  	 	          |    ---      	 	     | 26/09/2023            	 	 |
|                                                        |     feature/profile                     	     |                   0a9afe70ce7bb8c947c980752f0df3fece40372a                                    	 	                    |     feat(petprofile): add petprofile.                                        	 	     |   ---        	 	    | 25/09/2023           	 	  |
|                                                        |      feature/profile                  	       |                   0ca9b85a2282572008b8c816cfae99ef7d375e33                                     	 	                   |     feat(vetprofile): add vetprofile.                                        	 	     |   ---        	 	    | 25/09/2023           	 	  |
|                                                        |       feature/map                     	       |                   39b9980875f5c94c792bc60e84e498c8082ad129                                    	 	                    |            feat(map): add map.                                        	 	            |   ---        	 	    | 25/09/2023           	 	  |
|                                                        |    feature/faq                          	     | 758f471366501fd48f0a9121b9d67e3c3d91384a                                                                         	 	 |            feat(faq): add faq.                                       	 	             |     ---     	 	     | 25/09/2023           	 	  |
|                                                        |        developer                     	        |         dcc1aea730b29229cea9eb6fb13574f957a0b201                                                        	 	          |        feat(main): Initial Commit.                                        	 	        |     ---     	 	     | 25/09/2023           	 	  |



### 5.2.1.4. Execution Evidence for Sprint Review.
En este Sprint 1 se logró la implementación de la landing page de MapVet, los miembros cumplieron con las tareas asignadas durante el sprint y gracias a esto se concretó con su implementación y despliegue. A continución, una vista de las principales pantallas de la landing page.

![Landing 1](https://i.ibb.co/tZhpqC7/Landing-Page.png)

![Landing 2](https://i.ibb.co/vXqFkx4/Landing-Page-About.png)

![Landing 3](https://i.ibb.co/0cyVJtY/Landing-Page-Recommendation.png)

![Landing 4](https://i.ibb.co/mv6tpT7/Landing-Page-Faq.png)

![Landing 5](https://i.ibb.co/XzvX1Sk/Landing-Page-Pet.png)

### 5.2.1.5.  Software Deployment Evidence for Sprint Review.
Para la implementación de nuestra página, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "main" que previamente se encontrba en la rama develop.

**Link de la Landing Page desplegada:**  https://upc-coders.github.io/MapVet-LandingPage/
### 5.2.1.6. Team Collaboration Insights during Sprint.
En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo

![commits-1](https://i.ibb.co/C13NXhn/gitflow-pulse.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo.

![commits-2](https://i.ibb.co/KGKscYG/gitflow-traffic.png)

Estos gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![network](https://i.ibb.co/ZMKsc09/gitflow-network.png)

### 5.2.2. Sprint 2
En esta sección, se detalla el proceso completo de implementación y despliegue de la aplicación web desarrollada con el framework Vue. Se aborda de manera grupal, detallando planificación del avance desde la concepción del Product Backlog hasta la puesta en producción de este componente en nuestro proyecto.
### 5.2.2.1. Sprint Planning 2
En el Sprint Planning 2 se planificó para la elaboración de la aplicación web del proyecto. Mediante una reunión grupal se determinaron y acordaron distintas tareas para su elaboración

|             Sprint #             |                                                                                                                                  Sprint 2                                                                                                                                   | 
|:--------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  **Sprint Planning Background**  |                                                                                                                                                                                                                                                                             |
|               Date               |                                                                                                                                 	2023-09-25                                                                                                                                 |
|               Time               |                                                                                                                                  10:00 PM	                                                                                                                                  |
|             Location             |                                                                                                                             	Virtual (Discord)                                                                                                                              |
|           Prepared By            |                                                                                                                     	 Juan Calisaya, Sebastian Ramirez                                                                                                                      |
|            Attendees             |                                                    Renato German Reyes Valenzuela / Juan Jesús Calisaya Sánchez / Josue Daniel Valverde Lopez / Sebastian Andre Ramirez Mendez / Juliana Yauricasa Seguil              	                                                    |
|    Sprint 2 - Review Summary     | Se asignaron tasks para los integrantes del grupo para la elaboración de la aplicación web. Se acordó que la fecha de culminación de los tasks será hasta el 26 de septiembre de 2023                                                                                     	 |
| Sprint 2 - Retrospective Summary |                                    Los integrantes se mostraron conformes con la distribución y fechas de entrega de los tasks                                                                                                        	                                     |
|  **Sprint Goal & User Stories**  |                                                                                                                                                                                                                                                                             |
|          Sprint 2 Goal           |                                    Construcción y despliegue de la aplicación web en su totalidad, en un lapso de 3 días                                                                                                               	                                    |
|        Sprint 2 Velocity         |                                                                                                30                                                                         	                                                                                                 |
|       Sum of Story Points        |                                                                                                            29                                                  	                                                                                                            |

### 5.2.2.2. Sprint Backlog 2
El objetivo principal del Sprint 2 es lograr la implementación de la aplicación web del proyecto, a continuación se muestra una tabla en la cual se presentan las historias de usuario y las tareas que se desprenden de cada una. Se destaca en importancia la asignación y el estado de la tarea.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 2</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>Description</strong></td>
    <td align="center"> <strong>Estimation (Hours)</strong></td>
    <td align="center"> <strong>Assigned To</strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="2" align="center"> ID </td>
    <td rowspan="2" align="center"> US21: Ver Preguntas Frecuentes (FAQ) </td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir preguntas</td>
    <td align="justify"> Se añadirán las preguntas frecuentes en cards</td>
    <td align="center"> 1 </td>
    <td align="center"> Sebastian Ramirez </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Redirección de secciones </td>
    <td align="center"> Agregar un navbar para redirigirse otras secciones de la landing page</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

 

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US 17: Hacer una cita</td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir campos de información</td>
    <td align="center"> Se añaden los campos para que sean completados por el usuario y confirme con el boton "Nueva Cita" </td>
    <td align="center"> 3</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Seleccionar veterinaria</td>
    <td align="center"> Se mostrará la información final de los detalles de la cita y un botón "Reservar" para confirmar la cita</td>
    <td align="center"> 2</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Muestra de las citas registradas </td>
    <td align="center"> Se muestran en cards las citas registradas con su respectiva información </td>
    <td align="center"> 2</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center"> Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center">  US 16: Apartado de recomendaciones </td>
    <td align="center"> TA01 </td>
    <td align="center"> Redirección de secciones </td>
    <td align="center"> Agregar un navbar para redirigirse otras secciones de la landing page</td>
    <td align="center"> 1</td>
    <td align="center"> Renato Reyes</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Muestra de veterinarias recomendadas </td>
    <td align="center"> Se agrega una foto de la veterinaria recomendada en la cual se puede hacer click para mostrar más detalles </td>
    <td align="center"> 2</td>
    <td align="center"> Renato Reyes</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Opciones disponibles</td>
    <td align="center"> Se muestran opciones de los servicios que ofrece la veterinaria para poder elegir</td>
    <td align="center"> 3</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center"> Done</td>
  </tr>

</table>

### 5.2.2.3. Development Evidence for Sprint Review.

|                  Repository                   |               Branch                |                                 Commit Id                                 |                                     Commit Message                                     | Commit Message Body |   Committed on (Date)   |
|:---------------------------------------------:|:-----------------------------------:|:-------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|:-------------------:|:-----------------------:|
| https://github.com/upc-coders/Frontend-MapVet |           feature/routes            |              e32bd3144676b31acab2d0a4cebd96d1c929efa1   	 	               |                          feat(routes): routes added.      	 	                          |    ---      	 	     |  29/09/2023        	 	  |
|                                               |     feature/recommendations  	      |     271e7b153910edbd6682082a58a4e61be96458d4                     	 	      |            feat(recommendations): section recommendations               	 	            |    ---       	 	    | 29/09/2023          	 	 |
|                                               |       feature/faq           	       |     7588a4d363bb34a54918d6f2e3d3bdc19f9d88d9                     	 	      |                  feat(faq): faq added                             	 	                  |    ---       	 	    |  29/09/2023        	 	  |
|                                               |   feature/appointment          	    | af87603cb001f6c580f267b13f4eff3dabae86e8                              	 	 |             feat(develop): assets added.                              	 	              |    ---       	 	    | 29/09/2023         	 	  |
|                                               |  feature/appointment             	  | 9d0a78aeaea28729a8386d53f30f6ee654b62585                              	 	 |    feat(appointment): section appointment added.                               	 	     |    ---       	 	    | 29/09/2023          	 	 |
|                                               |  feature/appointment            	   |                 e46c294eb33866f0ed4a607af57c222dd9e742dd                  | feat(appointment): section appointment service added.                              	 	 |    ---       	 	    |  29/09/2023        	 	  |
|                                               | feature/appointment               	 |                 414f9ae4f70c4a68bc0d89270e2132924659b9b2                  |          feat(appointment): component added.                              	 	          |    ---       	 	    | 29/09/2023          	 	 |
|                                               | feature/appointment               	 |                 d9dbea3832a370b268dee43d4a9bfb222b29eecb                  |     feat(appointment): index.js update                                        	 	      |    ---       	 	    |  29/09/2023        	 	  |
|                                               | feature/appointment              	  | 6e367faf7962dce91eb7f220e0bf4f6d5413f66b                              	 	 |      feat(appointment): routes update.                                       	 	       |    ---       	 	    | 29/09/2023          	 	 |
|                                               |       develop              	        |   b0a89df13a4b8697c4674e7ff68a76449fafa048                          	 	   |             fix(home): home fixed                                      	 	             |    ---       	 	    | 29/09/2023          	 	 |


### 5.2.2.5. Execution Evidence for Sprint Review.

En este segundo sprint, hemos completado con éxito la implementación de la página web de MapVet. Todos los miembros del equipo han cumplido con sus tareas asignadas, lo que ha permitido la realización y puesta en marcha del sitio web. A continuación, se muestran algunas de las pantallas clave de la página web.

![Paginaweb-landing](https://i.ibb.co/Fsk0dkP/landingpage.jpg)

![Paginaweb-vets](https://i.ibb.co/g3y0mSM/veterinarias.jpg)

![Paginaweb-vets2](https://i.ibb.co/GVSGX7H/veterinarias2.jpg)

![Paginaweb-appoinments](https://i.ibb.co/7yWsCFt/appoinments.jpg)

![Paginaweb-faq](https://i.ibb.co/s5yYQ1N/faq.jpg)

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el segundo sprint, hemos logrado un progreso sustancial en la documentación de nuestros servicios web. Hemos documentado varios puntos de acceso (Endpoints) que son esenciales para el funcionamiento de nuestra aplicación. A continuación, proporcionamos detalles sobre los puntos de acceso documentados, ejemplos de interacción y enlaces a la documentación desplegada.

Repositorio: https://github.com/upc-coders/Frontend-MapVet/tree/develop

![Commmits](https://i.ibb.co/TczqBKC/commits.png)

**Endpoints Documentados**

|  Endpoint	   | Verbo HTTP  | Parámetros | Ejemplo de Llamada |                              
|:------------:|:-------------------:|:----------:|:------------------:|
| /appoinment  |     GET      |  Ninguno   | GET<br/>/tutorials |
|    /data     |     GET      |  Ninguno   |    GET<br/>/faq    |


### 5.2.2.7.  Software Deployment Evidence for Sprint Review.

Para la implementación de nuestra página, optamos por utilizar GitHub para el control de versiones y colaboración en equipo. En este proceso, creamos un repositorio donde a partir de ramas colaboramos cada integrante del equipo, al finalizar pasamos todo a la rama develop. Netlify fue la plataforma que utilizamos para el despliegue de la página web.

Enlace de la pagina web: https://frontend-map-vet.vercel.app/

![Paginaweb-landing-desplegado](https://i.ibb.co/kgjFqmT/landing-despliegue.png)

![Paginaweb-vets-desplegado](https://i.ibb.co/yyjpgd3/vet-despliegue.png)

![Paginaweb-appoinments-desplegado](https://i.ibb.co/tZ85SJ0/appoinment-despliegue.png)

![Paginaweb-faq-desplegado](https://i.ibb.co/DRwyFSJ/faq-desplieque.png)

### 5.2.2.8. Team Collaboration Insights during Sprint.

En el segundo sprint, nuestro equipo se enfocó en la implementación del frontend y la revisión y mejora del informe. Utilizamos la metodología Gitflow y seguimos un formato Markdown para la colaboración, y los cinco miembros del equipo participaron de manera efectiva. Durante este período, se llevaron a cabo las tareas de desarrollo del frontend y se realizaron las correcciones necesarias en el informe y la página de inicio.

Imagenes de los commits para el reporte

![Commmits-report](https://i.ibb.co/bPxbbMJ/commits-report.png)

Imagenes de los commits del FrontEnd

![Commmits](https://i.ibb.co/TczqBKC/commits.png)

Imagenes de los commits del landing page

![Commmits-Landing](https://i.ibb.co/djvshSf/commits-landing.png)

### 5.2.3. Sprint 3
En esta sección, se detalla el proceso completo de implementación en fase inicial del backend desarrollado en ASP.NET. Se aborda de manera grupal, detallando planificación del avance desde la concepción del Product Backlog hasta la puesta en producción de este componente en nuestro proyecto.
### 5.2.3.1. Sprint Planning 3
En el Sprint Planning 3 se planificó para la elaboración del backend del proyecto. Mediante una reunión grupal se determinaron y acordaron distintas tareas para su elaboración

|             Sprint #             |                                                                                                                             Sprint 3                                                                                                                             | 
|:--------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  **Sprint Planning Background**  |                                                                                                                                                                                                                                                                  |
|               Date               |                                                                                                                           	2023-10-29                                                                                                                            |
|               Time               |                                                                                                                             6:00 PM	                                                                                                                             |
|             Location             |                                                                                                                        	Virtual (Discord)                                                                                                                        |
|           Prepared By            |                                                                                                               	 Daniel Valverde, Sebastian Ramirez                                                                                                               |
|            Attendees             |                                                               Juan Jesús Calisaya Sánchez / Josue Daniel Valverde Lopez / Sebastian Andre Ramirez Mendez / Juliana Yauricasa Seguil              	                                                               |
|    Sprint 2 - Review Summary     | Se asignaron tasks para los integrantes del grupo para la elaboración del backend. Se acordó que la fecha de culminación de los tasks será hasta el 1 de noviembre de 2023                                                                                     	 |
| Sprint 2 - Retrospective Summary |                               Los integrantes se mostraron conformes con la distribución y fechas de entrega de los tasks                                                                                                        	                               |
|  **Sprint Goal & User Stories**  |                                                                                                                                                                                                                                                                  |
|          Sprint 2 Goal           |                                        Construcción y del backend en fase inicial, en un lapso de 3 días                                                                                                               	                                         |
|        Sprint 2 Velocity         |                                                                                           25                                                                         	                                                                                           |
|       Sum of Story Points        |                                                                                                      28                                                  	                                                                                                       |

### 5.2.2.2. Sprint Backlog 3
El objetivo principal del Sprint 3 es lograr la implementación en fase incial del backend, a continuación se muestra una tabla en la cual se presentan las historias de usuario y las tareas que se desprenden de cada una. Se destaca en importancia la asignación y el estado de la tarea.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 3</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>Description</strong></td>
    <td align="center"> <strong>Estimation (Hours)</strong></td>
    <td align="center"> <strong>Assigned To</strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="3" align="center"> US22 </td>
    <td rowspan="3" align="center"> Acceder al Endpoint Citas  </td>
    <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context de Citas</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Sebastian Ramirez </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

 <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> US23 </td>
    <td rowspan="3" align="center"> Acceder a Endpoint Productos</td>
     <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context de la Tienda</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Daniel Valverde </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Daniel Valverde</td>
    <td align="center">Done</td>
  </tr>

  <tr>
     <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center">Done</td>
  </tr>

 <tr>
    <td rowspan="3" align="center"> US24 </td>
    <td rowspan="3" align="center"> Acceder a Endpoint Identification</td>
     <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context Identification</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Juliana Yauricasa </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Juliana Yauricasa </td>
    <td align="center">Done</td>
  </tr>

  <tr>
     <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center">Done</td>
  </tr>

</table>

### 5.2.3.3. Development Evidence for Sprint Review.

#### Frontend-MapVet

|                  Repository                   |      Branch      |                Commit Id                 |                         Commit Message                          | Commit Message Body | Committed on (Date) |
|:---------------------------------------------:|:----------------:|:----------------------------------------:|:---------------------------------------------------------------:|:-------------------:|:-------------------:|
| https://github.com/upc-coders/Frontend-MapVet |  feature/store   | 61dda1e7b98fb582b25e035b3770586af2e6ad8b |               feat(store): added store component                |      ---     	      |     24/10/2023      |
|                                               |  feature/store   | 05d36106fe135d7e9ba5331001e3de14ccc4e39b |                feat(store): added store service                 |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | fd04d3c08e59af78d950da6f0427ec855614a522 |          feat(store): added store route configuration           |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | acf31f67d18a877c8e1552d531a7547766dcd598 |       feat(store): added store api service configuration        |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | affd049ae89c72d2b7aaa81b35114d489b2f2c60 |           feat(store): added toolbar store component            |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | fc89b51d54270603a8315180752bac423a880749 |            feat(store): added cards store component             |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | fd2763131da32ca7175357244fbddef53a692b1f |           feat(store): added sidebar store component            |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/store   | 6f15cd2007da5ac5096cd55a2dc295dcd7e6fa4d |            feat(store): added style store component             |    ---       	 	    |    24/10/2023  	    |
|                                               | feature/register | acb20b2b89013384f87db6645c3b37847c73ed2e |            feat(register): added register component.            |    ---       	 	    |    24/10/2023  	    |
|                                               | feature/register | 320fd982c7cb9d29819e2220dcbbb65c3bf12acb |    feat(register): set the path for the registry component.     |    ---       	 	    |    24/10/2023  	    |
|                                               | feature/register | 2bc4eff12c303293c703033074da17ca42604721 |         feat(register): added style register component.         |    ---       	 	    |    24/10/2023  	    |
|                                               | feature/register | 716fab25dd8dbddabb0e7b0e7d880252e1747f6e |   feat(register): create user service for register component.   |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/login   | 12ca29c34f7540cbc055391263da55531ad2353f |         feat(login): created and added login component.         |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/login   | a0b607c9f61eb1e9a029831d1837986581ca7e91 |       feat(login): set the path for the login component.        |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/login   | 3b1c219746e4d97e39397f16bbf8818de4a7131a |            feat(login): added style login component.            |    ---       	 	    |    24/10/2023  	    |
|                                               |  feature/login   | cb55785100a8dcc8a4aaafbe7c300ce06ba245b5 | feat(login): create method in user service for login component. |    ---       	 	    |    24/10/2023  	    |
|                                               |     develop      | a05fb198766be3d4fb9f554390299def8fdff101 |                   feat(develop): faq updated.                   |    ---       	 	    |    27/10/2023  	    |
|                                               |     develop      | 2f1db8da07cd4bde6f409f278759e759f6413650 |                 feat(develop): profile updated.                 |    ---       	 	    |    28/10/2023  	    |
|                                               |     develop      | f122d91d8ca0d6b266bee6b375f9ef67e40de929 |                 feat(develop): profile updated.                 |    ---       	 	    |    28/10/2023  	    |
|                                               |     develop      | f519899c643e02ece5abf9d8b38bd3550ea2c3e2 |                 feat(develop): endpoints added.                 |    ---       	 	    |    30/10/2023  	    |
|                                               |     develop      | 8c7acb79d60124e8312d220f9231aafa8107321d |                     fix(develop): home fixed                    |    ---       	 	    |    31/10/2023  	    |

#### Backend-VetCare

|                  Repository                   |              Branch              |                                     Commit Id                                      |                                              Commit Message                                              | Commit Message Body |   Committed on (Date)   |
|:---------------------------------------------:|:--------------------------------:|:----------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|:-------------------:|:-----------------------:|
| https://github.com/upc-coders/Backend-VetCare |             develop              |                   e8076f091e96348a925246b587c68085d751f52f   	 	                   |                                          initial commit     	 	                                          |    ---      	 	     |  29/10/2023        	 	  |
|                                               |            develop  	            |          fb8799b6e1692151ba59aa7987cce76140638433                    	 	           |                      feat(develop): domain of shared implemmented               	 	                      |    ---       	 	    | 29/10/2023          	 	 |
|                                               |             develop	             |           513384b37a0f6f3179e9342082b90c001c1a42dd                   	 	           |                feat(develop): extensions of shared added.                            	 	                 |    ---       	 	    | 29/10/2023          	 	 |
|                                               |           develop   	            |     f9cbfdcb67859c3d8076efc663214c811e0e0c54                              	 	      |            feat(develop): persistence of shared added.                                   	 	             |    ---       	 	    | 29/10/2023          	 	 |
|                                               |       feature/store     	        |     e17d207af8eb64763798ecf57bbd9636fd6ac12c                              	 	      |                 feat(store): added store domain                                      	 	                 |    ---       	 	    | 29/10/2023          	 	 |
|                                               |     feature/store          	     |   6ecccf172c0d5b1a731fc8f929b9a7b31dac801c                                   	 	   |              feat(store): added product resource                                       	 	               |    ---       	 	    | 30/10/2023          	 	 |
|                                               |    feature/store            	    |  f0d3b4a2008990a5ddf38481a5dad3b4d329acc3                                    	 	   |               feat(store): added product service                                       	 	               |    ---       	 	    | 30/10/2023          	 	 |
|                                               |    feature/store            	    |   0873fbbf3180af5b3c4378a0824afb2572c134ee                                   	 	   |               feat(store): added product mapping                                       	 	               |    ---       	 	    | 30/10/2023          	 	 |
|                                               |    feature/store           	     |   c6855a6ab4ecb426158db6dae3498052decc8261                                   	 	   |             feat(store): added product persistence                                       	 	             |    ---       	 	    | 30/10/2023          	 	 |
|                                               |    feature/store           	     |   3b0be1656521469a79ceba0a2b6136bc91c665e6                                   	 	   |             feat(store): added product controller                                       	 	              |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | f275f2fb78c6312a66db5c75d4301fa5598f3009                                      	 	  |              fix(appointment): structure fixed.                                        	 	               |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | e55586f608c88ce836260858b5ea04150f872cfe                                       	 	 |             feat(appointment): IPetService added.                                       	 	              |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | db4c0d67ba00b179f84cd8be005e9d2d221eb4df                                       	 	 |         feat(appointment): IPrescriptionService added.                                       	 	         |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | ec522b1c8a8135adfd7640c68d22b3e688693a8e                                      	 	  |             feat(appointment): PetResponse added.                                       	 	              |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 031d929ed614d69924bf841b9e68e28fe6f06793                                      	 	  |         feat(appointment): PrescriptionResponse added.                                       	 	         |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 |  f0bdf912d2cc56734160b12301479cd9a13bb904                                     	 	  |        feat(appointment): ModelToResourceProfile added.                                       	 	        |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 21589a9ab62831fc364e8adc2b02c2e3ca0ed61b                                      	 	  |        feat(appointment): ResourceToModelProfile added.                                       	 	        |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | a1f6a4e7d53056f9b443a636240584834dfa5556                                      	 	  |            feat(appointment): PetRepository added.                                       	 	             |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | f8d8c3ef9e4d8f4de01399649edcf8631af9a08a                                      	 	  |        feat(appointment): PrescriptionRepository added.                                       	 	        |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 2df63e52552957ddf6ddb7b61ae40a808e9d4360                                      	 	  |              feat(appointment): PetResource added.                                      	 	              |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 46cc1ed1892e7c9069e64963d9b83e419680f791                                      	 	  |         feat(appointment): PrescriptionResource added.                                       	 	         |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 1e2619b9a49ef4498e7ea9e514ed7782d13c86ef                                      	 	  |           feat(appointment): SavePetResource added.                                       	 	            |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 |  afafa06abbaf536652ff0728fd7391b296974ed2                                     	 	  |       feat(appointment): SavePrescriptionResource added.                                      	 	        |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 141d242f63eb49690525f0365e518f159aa97168                                       	 	 |              feat(appointment): PetService added.                                       	 	              |    ---       	 	    | 30/10/2023          	 	 |
|                                               | feature/appointment            	 | 602fcd035353ae9dc21ef776aca6ab626a29ce55                                      	 	  |         feat(appointment): PrescriptionService added.                                       	 	          |    ---       	 	    | 30/10/2023          	 	 |
|                                               |      feature/identification      |                      df1156c646c6a9f4ad3e4cf18674193fdd4601ff                      |                                 feat(identification): Added User model.                                  |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      2a12340a945a07f67d209e0766591c0ad22640de                      |                      feat(identification): Added authenticate request and response.                      |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      2e0115085b69baa86f6fe40498ba9697f080c738                      |                      feat(identification): Added register and update communication.                      |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      862d47d4b5776fd5d5803c43952bafcb14edd99c                      |        feat(identification): Added mapping between register request and update request with user.        |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      18348d8cd171533df0e9cf9bcd650e42d3343070                      |                          feat(identification): Added interface user repository.                          |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      99dccc9716f38baebd41b190b578437a2e53ef36                      |                           feat(identification): Added interface user service.                            |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      a8d3353784832dc87f0c792e12686116360559a2                      |                              feat(identification): Implemented user table.                               |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      5fbf6e62c322b3eeecc50448073daa6d203f1c6e                      |                      feat(identification): created and implemented user repository.                      |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      72a9ba49ad165ec6623c04e873edea909dc4461e                      |                                        chore: added dependencies.                                        |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      24125a8548269a374f20209816bf85fd6ad3a558                      |                         feat(identification): Implemented user service methods.                          |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      ea4cbfa6bce8e98ca0ce8df67adecfe4b183af33                      |                      feat(identification): Added users controller and set program.                       |         ---         |       02/11/2023        |      
|                                               |      feature/identification      |                      df1156c646c6a9f4ad3e4cf18674193fdd4601ff                      |                                 feat(identification): Added User model.                                  |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      d51f69e79492f18ad860f85d159bcff8d2a308fc                      |              feat(identification): Added attribute allow anonymous and attribute authorize.              |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      a49ab068fa89e39519919c5d50492ad1faf4112a                      |                feat(identification): Created and implemented generate and validate token.                |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      d49dd08ba7b2eb757957f5997abd5636c6f1a41c                      |              feat(identification): Implemented request delegate, settings and set program.               |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      85f0874c431af0490580348148e7a89ff6ea898c                      | feat(identification): Modified user service, corrected references in user controller and placed a token. |         ---         |       02/11/2023        |     
|                                               |      feature/identification      |                      226833e520beb278037c2807bdcb0c406f37b683                      |                       chore(identification): Update Swagger to allow token usage.                        |         ---         |       02/11/2023        | 
|                                               |      feature/identification      |                      359325d0f9571a6ff786ba2d48fb6d0428ec7bab                      |                        feat(identification): Update generate and validate token.                         |         ---         |       02/11/2023        |   

### 5.2.3.4. Testing Suite Evidence for Sprint Review.

A continuación, se detalla las pruebas que se han llevado a cabo en el backend de la aplicación web VetCare utilizando el plugin SpecFlow for Rider. Estas pruebas se han centrado en validar las funcionalidad de creación en la aplicación. A continuación, se presentan los aspectos clave de nuestro proceso de pruebas:

**Definición de Escenarios de Prueba:**
Hemos empleado la notación Gherkin para definir escenarios de prueba en archivos de características (.feature). Cada escenario describe pasos, datos de entrada y resultados esperados relacionados con la creación de productos.

<a href="https://ibb.co/9ZwjMDt"><img src="https://i.ibb.co/TWK5CfL/product.png" alt="product" border="0"></a>

<a href="https://ibb.co/z2WZ2vZ"><img src="https://i.ibb.co/2M0dM4d/pet.png" alt="pet" border="0"></a>

**Implementación de Pasos:**
Los pasos definidos en los archivos de características se han implementado en código C#. Estos pasos contienen la lógica necesaria para interactuar con la aplicación web y llevar a cabo la creación de productos.

<a href="https://ibb.co/BrkvZbq"><img src="https://i.ibb.co/wwt8WVM/implementacion.png" alt="implementacion" border="0"></a>

**Ejecución de Pruebas:**
Hemos utilizado el plugin SpecFlow for Rider para ejecutar los escenarios de prueba. Durante estas pruebas, hemos verificado que el proceso de creación de productos se realiza de acuerdo con nuestros requisitos y expectativas.

<a href="https://ibb.co/XD45DyR"><img src="https://i.ibb.co/jz5wzVX/testsp.png" alt="testsp" border="0"></a>

El objetivo de este proceso de pruebas es garantizar la calidad de nuestra aplicación web y proporcionar una experiencia confiable a nuestros usuarios. Estamos seguros de que las pruebas realizadas han contribuido significativamente a este objetivo.

#### VetCare.API-Test

|                  Repository                    |      Branch   |   Commit Id                              |                         Commit Message                         | Commit Message Body |  Committed on (Date)  |
|:----------------------------------------------:|:-------------:|:----------------------------------------:|:--------------------------------------------------------------:|:-------------------:|:---------------------:|
| https://github.com/upc-coders/VetCare.API-Test |     develop   | 47402700d5fc08a76181b0410c8424dc68b2d738 |             chore: Roll back the project to net 6.             |         ---         |  04/11/2023        	  |
|                                                |    develop    | 066afd4e38a9d4da042c8db8c4d5ee5b0ca6ffb1 |           feat: Added new project VetCare.API.Test.            |    ---        	     | 04/11/2023          	 |
|                                                |    develop    | e67f8e2715bff6d50f6359c7ced5ee5ee00c59a8 |                chore: Installed new dependency.                |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | 77fb754f047bf94fa326d97761ca853cca9c8504 |         test: Added feature test and step definitions.         |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | 5afdc46c6845b13f10354e3317b21cb82af5b96b | test: Implemented products tests feature and step definitions. |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | eb95ba1ed411a270fac1d09e620b69ae21335673 |            test: Modify Program.cs and change port.            |     ---       	     |    04/11/2023   	     |


### 5.2.3.5. Execution Evidence for Sprint Review.

En este apartado se presentan las capturas de las vistas que se realizaron en este Sprint.  
En este Sprint se trabajó en la implementación del Backend empleando Endpoints.

Se implementó el Endpoint para la gestión del perfil de la mascota.   
![PetProfile](https://i.ibb.co/YpgdC0m/Screenshot-1.jpg)  


Se implementó el Endpoint para la gestión de las citas.  
![Appointments](https://i.ibb.co/YTzmQp2/Screenshot-2.jpg)  


Se implementó el Endpoint para la gestión de la tienda.  
![Store](https://i.ibb.co/MVBRpsc/Screenshot-3.jpg)  

Se implementó el Endpoint para la autenticación del usuario.

<a href="https://ibb.co/4TD6Q4K"><img src="https://i.ibb.co/yyMw3gd/login.png" alt="login" border="0"></a>
<a href="https://ibb.co/JFztKTD"><img src="https://i.ibb.co/XkzLbPc/registro.png" alt="registro" border="0"></a>

### 5.2.3.6. Services Documentation Evidence for Sprint Review
En esta sección se presentan los endspoints realizados en el sprint y se realizan capturas de las acciones CRUD que se han empleado. Tales como los enlaces que se están utilizando para los Endpoints.

Link del Swagger UI: https://vetcareapi.azurewebsites.net/swagger/index.html

<table>
 

   <tr>
    <td align="center" colspan="4"> <strong>Services</strong></td>
    
  </tr>
  <tr>
    <td align="center"> <strong>Endpoint</strong> </td>
    <td align="center"> <strong>Acciones implementadas</strong></td>
    <td align="center"> <strong>Enlaces</strong> </td>
    <td align="center"> <strong>Acciones soportadas</strong></td>
    
   </td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="4" align="center"> Pets </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /pets, correspondiente al CRUD de un perfil de mascota.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/pets </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/pets </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/pets </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/pets </td>
    <td align="center"> DELETE </td>
  </tr>

   <!---------------------------------------------------------------------- -->

<tr>
    <td rowspan="4" align="center"> Prescriptions </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /prescriptions, correspondiente al CRUD de una prescripción médica.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/prescriptions </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/prescriptions </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/prescriptions </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/prescriptions </td>
    <td align="center"> DELETE </td>
  </tr>

   <!---------------------------------------------------------------------- -->

<tr>
    <td rowspan="4" align="center"> Products </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /products, correspondiente al CRUD de una tienda.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/products </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/products </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/products </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/products </td>
    <td align="center"> DELETE </td>
  </tr>
</table>

------------------------  
<br>
* Método GET en el Endpoint /pets  

![GET](https://i.ibb.co/mhX1CYF/Screenshot-1.jpg) 

* Método POST en el Endpoint /pets

![POST](https://i.ibb.co/ynHdKC5/Screenshot-2.jpg) 

* Método PUT en el Endpoint /pets  

![PUT](https://i.ibb.co/TTvy77V/Screenshot-3.jpg) 

* Método DELETE en el Endpoint /pets 

![DELETE](https://i.ibb.co/SPZ6dMV/Screenshot-4.jpg) 

* Método GET en el Endpoint /prescriptions

![GET](https://i.ibb.co/RPHNbnC/Screenshot-5.jpg) 

* Método POST en el Endpoint /prescriptions

![POST](https://i.ibb.co/0jX1mXZ/Screenshot-6.jpg)

* Método PUT en el Endpoint /prescriptions  

![PUT](https://i.ibb.co/DkQtX4q/Screenshot-7.jpg)

* Método DELETE en el Endpoint /prescriptions  

![DELETE](https://i.ibb.co/GPGmCVH/Screenshot-8.jpg)

* Método GET en el Endpoint /products 

![GET](https://i.ibb.co/PWNXMYw/Screenshot-9.jpg)

* Método POST en el Endpoint /products

![POST](https://i.ibb.co/qNNZ6nK/Screenshot-10.jpg)

* Método PUT en el Endpoint /products 

![PUT](https://i.ibb.co/9NfVDzZ/Screenshot-11.jpg)

* Método DELETE en el Endpoint /products

![DELETE](https://i.ibb.co/3BLCJYF/Screenshot-12.jpg)



### 5.2.3.7.  Software Deployment Evidence for Sprint Review.

En esta sección se resume los procesos realizados en relación con Deployment
durante este Sprint.   
Llevamos a cabo la implementación en dos plataformas altamente confiables. Utilizamos Azure para configurar el entorno del Web Application, aprovechando sus capacidades y recursos, mientras que optamos por SmarterASP.NET para la implementación de la base de datos MySQL, garantizando así una solución sólida y eficiente para nuestro despliegue.  
<br>
En este paso realizamos la creación de nuestra cuenta en Azure para poder administrar la subscripción que tenemos en esta plataforma.  

![Create Azure Portal](https://i.ibb.co/ZNq1YSK/Screenshot-1.jpg)  

Para incorporar recursos relacionados a la solución de Azure, es necesario crear un grupo de recursos que permita el uso de un contenedor adecuado. Debemos de colocarle un nombre a nuestro grupo de recursos y asegurarnos de que este no haya sido usado antes.

![Create resource group](https://i.ibb.co/pdzvq2y/Screenshot-2.jpg)

Una vez que hayamos validado nuestro grupo de recursos, procedemos a crear este contenedor, el cual nos permitirá incluir los recursos que serán utilizados en la solución.

![Successful creation resource group](https://i.ibb.co/vj4VVh1/Screenshot-3.jpg)

Luego, debemos crear el espacio para el API que se ejecutará dentro de la aplicación, donde se especifican los requisitos que se utilizarán en la solución.

![Create Web Application](https://i.ibb.co/0s1pB9S/Screenshot-4.jpg)

Debemos de seleccionar la pila de ejecución para la solución, es importante este paso ya que si no seleccionamos el correcto, nuestro API no será compatible. Seleccionamos .NET7 (STS).

![Select .NET 7 SLS](https://i.ibb.co/q5Zh80D/Screenshot-5.jpg)

En este apartado también seleccionamos el plan que deseamos utilizar para la solución.

![Select plan](https://i.ibb.co/PF3wT7g/Screenshot-6.jpg)

Esta página nos ayuda muchísimo para la creación de la base de datos, ya que nos proporciona un enlace que utilizaremos en la solución de nuestro proyecto.

![Create account on SmarterASP](https://i.ibb.co/6RmF33K/Screenshot-7.jpg)  

En esta parte realizamos la gestión de nuestra cuenta para el hosting de nuestra base de datos (MySQL).

![Create Hosting account](https://i.ibb.co/Mp01cjK/Screenshot-8.jpg)

Una vez dentro de nuestra cuenta, nos dirigimos a la pestaña de Databases, y seleccionamos la base de datos que deseamos utilizar.

![Create database on MySQL](https://i.ibb.co/9YyYbRK/Screenshot-9.jpg)

Nos proporcionará la cadena de conexión para la base de datos.

![Connection String Examples](https://i.ibb.co/yXchPyt/Screenshot-10.jpg)

Luego de haber realizado los pasos previos, abrimos nuestra solución con Visual Studio 2022 y la seleccionamos y seleccionamos la opción de Publicación en Azure.

![Select Azure](https://i.ibb.co/dcFtsvw/Screenshot-11.jpg)

Es importante seleccionar Azure App Service (Windows), ya que es esa la que hemos configurado en la plataforma.

![Select Azure App Service for Windows](https://i.ibb.co/VVrwgJX/Screenshot-12.jpg)

Seleccionamos la instancia de App Service que configuramos previamente en Azure.

![Select group of App Service implemmented on Azure](https://i.ibb.co/NScFp0V/Screenshot-13.jpg)

Saltamos este paso.  

![Skip sthep](https://i.ibb.co/FsDK7Fy/Screenshot-14.jpg)

Finalmente se creó el perfil para la publicación.

![Finish creating profile publish process](https://i.ibb.co/gTs0X0g/Screenshot-15.jpg)

Aquí simplemente le damos click a publicar y tendremos que esperar el proceso.

![Click on publish](https://i.ibb.co/SNZz72C/Screenshot-16.jpg)

Veremos en la consola la publicación de nuestra API y los posibles errores, en este caso, no se generó ninguno y podemos 

![Show console of API publish](https://i.ibb.co/YRfhXs2/Screenshot-17.jpg)

Utilizando el enlace generado en la consola, podemos ingresar al Swagger y tener interacción con nuestra API.

![Successful upload API](https://i.ibb.co/xXRsZrM/Screenshot-18.jpg)


### 5.2.3.8. Team Collaboration Insights during Sprint.
En esta entrega, nuestra meta principal fue la implementación en fase inicial del backend del proyecto. Para llevar a cabo este objetivo,
hicimos uso de diversas herramientas como GitHub, Rider, etc. A continuación,
vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo 
Durante este período también, se terminaron las tareas de desarrollo del frontend y se realizaron las correcciones necesarias en el informe aplicando la mejora continua.  

A continuación el gráfico de barras de la cantidad de commits por integrante  

![commits](https://i.ibb.co/2PjShKC/commits-sprint3.png)  

Registro de commits en las ramas creadas para el desarrollo del backend  

![commits2](https://i.ibb.co/dPpkrwy/commits-list.png)  

Lista de dependencias usadas en el proyecto backend  

![dependecys](https://i.ibb.co/PGhKyPc/dependencias.png)  

Cronología de los commits y la integración a la rama principal 'Develop'  

![network](https://i.ibb.co/mqBvHsK/network-sprint3.png)  

### 5.2.4. Sprint 4
En esta sección, se detalla el proceso completo de implementación en fase final del backend desarrollado en ASP.NET. y la culminación de vistas del frontend. Se aborda de manera grupal, detallando planificación del avance desde la concepción del Product Backlog hasta la puesta en producción de este componente en nuestro proyecto.
### 5.2.4.1. Sprint Planning 3
En el Sprint Planning 4 se planificó para la elaboración del backend del proyecto. Mediante una reunión grupal se determinaron y acordaron distintas tareas para su elaboración

|             Sprint #             |                                                                                                     Sprint 4                                                                                                      | 
|:--------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|  **Sprint Planning Background**  |                                                                                                                                                                                                                   |
|               Date               |                                                                                                    	2023-11-20                                                                                                    |
|               Time               |                                                                                                     6:00 PM	                                                                                                      |
|             Location             |                                                                                                	Virtual (Discord)                                                                                                 |
|           Prepared By            |                                                                                       	 Daniel Valverde, Sebastian Ramirez                                                                                        |
|            Attendees             |                                       Juan Jesús Calisaya Sánchez / Josue Daniel Valverde Lopez / Sebastian Andre Ramirez Mendez / Juliana Yauricasa Seguil              	                                        |
|    Sprint 2 - Review Summary     | Se asignaron tasks para los integrantes del grupo para la correción y adiciónde los útlimos elementos del frontend y backend.                                                                                   	 |
| Sprint 2 - Retrospective Summary |       Los integrantes se mostraron conformes con la distribución y fechas de entrega de los tasks                                                                                                        	        |
|  **Sprint Goal & User Stories**  |                                                                                                                                                                                                                   |
|          Sprint 4 Goal           |                                Culminación del backend y frontend                                                                                                               	                                 |
|        Sprint 4 Velocity         |                                                                   30                                                                         	                                                                    |
|       Sum of Story Points        |                                                                               32                                                  	                                                                               |

### 5.2.4.2. Sprint Backlog 4
El objetivo principal del Sprint 4 es lograr la implementación en fase final del frontend y backend, a continuación se muestra una tabla en la cual se presentan las historias de usuario y las tareas que se desprenden de cada una.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 3</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title</strong></td>
    <td align="center"> <strong>Description</strong></td>
    <td align="center"> <strong>Estimation (Hours)</strong></td>
    <td align="center"> <strong>Assigned To</strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="3" align="center"> US22 </td>
    <td rowspan="3" align="center"> Acceder al Endpoint Citas  </td>
    <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context de Citas</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Sebastian Ramirez </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

 <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> US23 </td>
    <td rowspan="3" align="center"> Acceder a Endpoint Productos</td>
     <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context de la Tienda</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Daniel Valverde </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Daniel Valverde</td>
    <td align="center">Done</td>
  </tr>

  <tr>
     <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Daniel Valverde</td>
    <td align="center">Done</td>
  </tr>

 <tr>
    <td rowspan="3" align="center"> US24 </td>
    <td rowspan="3" align="center"> Acceder a Endpoint Identification</td>
     <td align="center"> TA01 </td>
    <td align="center"> Crear bounded context</td>
    <td align="justify"> En el proyecto creado se añadirá el bounded context Identification</td>
    <td align="center"> 20 MIN </td>
    <td align="center"> Juliana Yauricasa </td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Configuración de archivos </td>
    <td align="center"> Agregar dentro del bounded context los archivos de configuración incluyendo (Controller, Domain, Persistence, etc)</td>
    <td align="center"> 3 </td>
    <td align="center"> Juliana Yauricasa </td>
    <td align="center">Done</td>
  </tr>

  <tr>
     <td align="center"> TA03 </td>
    <td align="center"> Configuración de archivos compartidos </td>
    <td align="center"> En la carpeta 'Shared' agrega el 'dbContext' para el modelo creado</td>
    <td align="center"> 1</td>
    <td align="center"> Juliana Yauricasa</td>
    <td align="center">Done</td>
  </tr>

</table>

### 5.2.4.3. Development Evidence for Sprint Review.

#### Frontend-MapVet

|                  Repository                   |                  Branch                  |                Commit Id                 |                Commit Message                | Commit Message Body | Committed on (Date) |
|:---------------------------------------------:|:----------------------------------------:|:----------------------------------------:|:--------------------------------------------:|:-------------------:|:-------------------:|
| https://github.com/upc-coders/Frontend-MapVet |              feature/store               | 61dda1e7b98fb582b25e035b3770586af2e6ad8b |      feat(store): added store component      |      ---     	      |     24/10/2023      |
|                                               |              feature/store               | 05d36106fe135d7e9ba5331001e3de14ccc4e39b |       feat(store): added store service       |    ---       	 	    |    24/10/2023  	    |
|                                               |              feature/store               | fd04d3c08e59af78d950da6f0427ec855614a522 | feat(store): added store route configuration |    ---       	 	    |    24/10/2023  	    |
|                                           |                    develop                    | 8c7acb79d60124e8312d220f9231aafa8107321d |         fix(develop): home fixed         |                ---       	 	                 |    31/10/2023  	    |

#### Backend-VetCare

|                  Repository                   |         Branch         |                                 Commit Id                                 |                                  Commit Message                                   | Commit Message Body |   Committed on (Date)   |
|:---------------------------------------------:|:----------------------:|:-------------------------------------------------------------------------:|:---------------------------------------------------------------------------------:|:-------------------:|:-----------------------:|
| https://github.com/upc-coders/Backend-VetCare |        develop         |              e8076f091e96348a925246b587c68085d751f52f   	 	               |                              initial commit     	 	                               |    ---      	 	     |  29/10/2023        	 	  |
|                                               |       develop  	       |      fb8799b6e1692151ba59aa7987cce76140638433                    	 	      |          feat(develop): domain of shared implemmented               	 	           |    ---       	 	    | 29/10/2023          	 	 |
|                                               |        develop	        |      513384b37a0f6f3179e9342082b90c001c1a42dd                   	 	       |     feat(develop): extensions of shared added.                            	 	     |    ---       	 	    | 29/10/2023          	 	 |
|                                               |      develop   	       | f9cbfdcb67859c3d8076efc663214c811e0e0c54                              	 	 | feat(develop): persistence of shared added.                                   	 	 |    ---       	 	    | 29/10/2023          	 	 |
|                                               | feature/identification |                 359325d0f9571a6ff786ba2d48fb6d0428ec7bab                  |             feat(identification): Update generate and validate token.             |         ---         |       02/11/2023        |   

### 5.2.4.4. Testing Suite Evidence for Sprint Review.

A continuación, se detalla las pruebas que se han llevado a cabo en el backend de la aplicación web VetCare utilizando el plugin SpecFlow for Rider. Estas pruebas se han centrado en validar las funcionalidad de creación en la aplicación. A continuación, se presentan los aspectos clave de nuestro proceso de pruebas:

**Definición de Escenarios de Prueba:**
Hemos empleado la notación Gherkin para definir escenarios de prueba en archivos de características (.feature). Cada escenario describe pasos, datos de entrada y resultados esperados relacionados con la creación de productos.

<a href="https://ibb.co/9ZwjMDt"><img src="https://i.ibb.co/TWK5CfL/product.png" alt="product" border="0"></a>

<a href="https://ibb.co/z2WZ2vZ"><img src="https://i.ibb.co/2M0dM4d/pet.png" alt="pet" border="0"></a>

**Implementación de Pasos:**
Los pasos definidos en los archivos de características se han implementado en código C#. Estos pasos contienen la lógica necesaria para interactuar con la aplicación web y llevar a cabo la creación de productos.

<a href="https://ibb.co/BrkvZbq"><img src="https://i.ibb.co/wwt8WVM/implementacion.png" alt="implementacion" border="0"></a>

**Ejecución de Pruebas:**
Hemos utilizado el plugin SpecFlow for Rider para ejecutar los escenarios de prueba. Durante estas pruebas, hemos verificado que el proceso de creación de productos se realiza de acuerdo con nuestros requisitos y expectativas.

<a href="https://ibb.co/XD45DyR"><img src="https://i.ibb.co/jz5wzVX/testsp.png" alt="testsp" border="0"></a>

El objetivo de este proceso de pruebas es garantizar la calidad de nuestra aplicación web y proporcionar una experiencia confiable a nuestros usuarios. Estamos seguros de que las pruebas realizadas han contribuido significativamente a este objetivo.

#### VetCare.API-Test

|                  Repository                    |      Branch   |   Commit Id                              |                         Commit Message                         | Commit Message Body |  Committed on (Date)  |
|:----------------------------------------------:|:-------------:|:----------------------------------------:|:--------------------------------------------------------------:|:-------------------:|:---------------------:|
| https://github.com/upc-coders/VetCare.API-Test |     develop   | 47402700d5fc08a76181b0410c8424dc68b2d738 |             chore: Roll back the project to net 6.             |         ---         |  04/11/2023        	  |
|                                                |    develop    | 066afd4e38a9d4da042c8db8c4d5ee5b0ca6ffb1 |           feat: Added new project VetCare.API.Test.            |    ---        	     | 04/11/2023          	 |
|                                                |    develop    | e67f8e2715bff6d50f6359c7ced5ee5ee00c59a8 |                chore: Installed new dependency.                |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | 77fb754f047bf94fa326d97761ca853cca9c8504 |         test: Added feature test and step definitions.         |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | 5afdc46c6845b13f10354e3317b21cb82af5b96b | test: Implemented products tests feature and step definitions. |     ---       	     | 04/11/2023          	 |
|                                                |    develop    | eb95ba1ed411a270fac1d09e620b69ae21335673 |            test: Modify Program.cs and change port.            |     ---       	     |    04/11/2023   	     |


### 5.2.4.5. Execution Evidence for Sprint Review.

### 5.2.4.6. Services Documentation Evidence for Sprint Review
En esta sección se presentan los endspoints realizados en el sprint y se realizan capturas de las acciones CRUD que se han empleado en este sprint. Tales como los enlaces que se están utilizando para los Endpoints.

Link del Swagger UI: https://vetcareapi.azurewebsites.net/swagger/index.html

<table>


   <tr>
    <td align="center" colspan="4"> <strong>Services</strong></td>

  </tr>
  <tr>
    <td align="center"> <strong>Endpoint</strong> </td>
    <td align="center"> <strong>Acciones implementadas</strong></td>
    <td align="center"> <strong>Enlaces</strong> </td>
    <td align="center"> <strong>Acciones soportadas</strong></td>

    </td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="4" align="center"> Questions </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /questions, correspondiente al CRUD de las preguntas frecuentes.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/questions </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/questions </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/questions </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/questions </td>
    <td align="center"> DELETE </td>
  </tr>

   <!---------------------------------------------------------------------- -->

<tr>
    <td rowspan="4" align="center"> Veterinary </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /veterinary, correspondiente al CRUD de la información de un médico veterinario.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/veterinaries </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/veterinaries </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/veterinaries </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/veterinaries </td>
    <td align="center"> DELETE </td>
  </tr>

   <!---------------------------------------------------------------------- -->

<tr>
    <td rowspan="4" align="center"> Vets </td>
    <td rowspan="4" align="center"> Implementar el Endpoint /vets, correspondiente al CRUD de una veterinaria.  </td>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/vets </td>
    <td align="center"> GET</td>
  </tr>

  <tr>
    <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/vets </td>
    <td align="center"> POST </td>
  </tr>

  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/vets </td>
    <td align="center"> PUT </td>
  </tr>
  <tr>
     <td align="center"> https://vetcareapi.azurewebsites.net/api/v1/vets </td>
    <td align="center"> DELETE </td>
  </tr>
</table>

### 5.2.4.7.  Software Deployment Evidence for Sprint Review.


### 5.2.3.8. Team Collaboration Insights during Sprint.
En esta entrega, nuestra meta principal fue la implementación en fase inicial del backend del proyecto. Para llevar a cabo este objetivo,
hicimos uso de diversas herramientas como GitHub, Rider, etc. A continuación,
vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo
Durante este período también, se terminaron las tareas de desarrollo del frontend y se realizaron las correcciones necesarias en el informe aplicando la mejora continua.

A continuación el gráfico de barras de la cantidad de commits por integrante




## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Información personal:**
-	¿Cuál es tu nombre?
-	¿Cuál es tu edad?
-	¿Cuál es tu ocupación profesional?

**Preguntas de interacción con la Landing Page y Web Application:**
- ¿Como se sintió al interactuar con el landing page?
- ¿Cómo se sintió al interactuar con la aplicación web y landing page?
- ¿Qué impresión tuvo al utilizar el apartado de citas de la aplicación web?
- ¿Cómo fue su experiencia al utilizar el menú y los botones?
- ¿Fue fácil para usted identificar las secciones importantes, como títulos y botones, en las diferentes vistas?
- ¿Considera que la información proporcionada es clara y precisa?
- ¿Cree que reservar una cita sería sencilla de llevar a cabo utilizando la interfaz?
- ¿Pudo navegar correctamente por los perfiles de las mascotas y agregar la suya?
- ¿Pudo navegar correctamente por la tienda y el carrito?

### 5.3.2. Registro de Entrevistas.

**Segmento: Dueños de mascotas**

| Entrevista | Nombre y Apellido |  Edad   |  Distrito  |           Timing inicial            |            Timing final             |
|:----------:|:-----------------:|:-------:|:----------:|:-----------------------------------:|:-----------------------------------:|
|     1      | Fernando, Lizano  | 18 años | San Miguel | [0:00](https://acortar.link/WiEbIE) | [8:42](https://acortar.link/zenRdQ) |

[![entrevista 1](https://i.ibb.co/8dNCLvk/1er-entrevista-due-os-de-mascotas.png)](https://acortar.link/WiEbIE)

Resumen:

En esta oportunidad se entrevistó a Fernando, Lizano de 18 años y reside en San Miguel, y, actualmente es estudiante, él nos comenta que fue fácil de navegar y se sintió muy cómodo con la landing page y aplicación web, además, la creación de citas fue práctico e intuitivo porque se puede ver donde en que veterinaria puede reservar una cita, por otro lado, utilizar el menú tanto los botones le parecieron sencillo se ve bien organizados y fáciles de encontrar y le gusto la paleta de colores, del mismo modo, el considera que la información estuvo clara y precisa. Por otro lado, le pareció muy buna idea agregar los perfiles a las mascotas, algo innovador, y pudo agregar correctamente el perfil de su mascota sin dificultad, asimismo, nos comenta que la tienda y el carrito de compras está bien hecha, nos menciona que le hubiese gustado tener una opción de eliminar un producto de su carrito, pero la navegación fue muy fluida y sin complicaciones.

---

| Entrevista | Nombre y Apellido |  Edad   |      Distrito       |           Timing inicial            |             Timing final             |
|:----------:|:-----------------:|:-------:|:-------------------:|:-----------------------------------:|:------------------------------------:|
|     2      | Rentería, Marcelo | 19 años | San Marin de Porres | [8:42](https://acortar.link/zenRdQ) | [18:50](https://acortar.link/Bbi1lN) |

[![entrevista 2](https://i.ibb.co/vLcvkrH/3era-entrevista-due-o-de-mascota.png)](https://acortar.link/zenRdQ)

Resumen:

A continuación, se le entrevisto a Marcelo Rentería de 19 años y reside en San Martin de Porres y, actualmente es estudiante. Nos comenta que le gustó la idea porque se puede usar bien, se ve completa y se puede usar bien algunas funciones, así mismo, le pareció bien y nos recomienda de poner la fecha de la cita como una sección más, además, al utilizar los botones del menú no comenta que es intuitivo y simple, del mismo modo, nos comentó que el botón de agregar mascota debería reubicarse donde se pueda acceder fácilmente ya que según vaya aumentando las mascotas el usuario tendrá que ir hasta debajo de la página para agrega otra, y, el considera que la información es clara y concisa. Por otro lado, el cree que si se le añade una vinculación con las veterinarias para hacer una cista más rápida y en el titulo poner un despliegue de la veterinarias recomendadas, sería más fácil y rápido la reserva de la cita, también, nos menciona que si pudo navegar correctamente en los perfiles de las mascotas, pero le gustaría que el botón esta más accesible por la cantidad de mascotas que pueda tener un usuario, de igual manera, el pudo navegar correctamente por la tienda y el carrito, lo vio completa.

---

| Entrevista | Nombre y Apellido |  Edad   |     Distrito      |           Timing inicial            |             Timing final             |
|:----------:|:-----------------:|:-------:|:-----------------:|:-----------------------------------:|:------------------------------------:|
|     3      | Gabriel Perkovic  | 19 años | Santiago de Surco | [18:50](https://acortar.link/Bbi1lN) | [27:24](https://acortar.link/OjAAtl) |

[![entrevista 3](https://i.ibb.co/WyJmdLQ/2da-entrevista-due-o-de-mascota.png)](https://acortar.link/Bbi1lN)

Resumen:

Nuestro entrevistado Gabriel Perkovic es un joven de 19 años, vive en Lima-Santiago de Surco y es estudiante, nos comenta que tubo una experiencia positiva para interactuar con la landing page y aplicación web, le pareció fácil de usar, los elementos están bien organizados y la información es clara, por otro lado, en el apartado de citas fue muy útil y fue sencillo usarla, además, nos menciona que el menú y los botones fueron muy intuitivos y no tuvo ningún problema por estar claramente etiquetados y botones fácil de identificar por tener un tamaño adecuado, así mismo el considera que la información es clara y concisa, porque todos los datos están bien organizado y es fácil de entender. Ahora bien, nos comenta que reservar las citas con la aplicación web seria muy sencillo ya que no requiere ningún conocimiento previo, de igual manera, el pudo agregar correctamente el perfil de su mascota, el proceso fue sencillo y no tuvo ningún problema, igualmente, el pudo navegar sin complicaciones en la tienda por los botones claros y el carrito le ayudo hacer un seguimiento de los artículos que ha agregado.

---




### 5.3.3. Evaluaciones según heurísticas.

#### ESCALA DE SEVERIDAD:
Los problemas serán evaluados utilizando la escala de gravedad que se describe a continuación:}

| Nivel |                                                                                                   	Descripción                                                                                                     |
|:-----:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|   1   |                       Se refiere a problemas superficiales que rara vez ocurren o que los usuarios pueden superar fácilmente. No es necesario abordarlos a menos que haya tiempo disponible.                       |
|   2   | Hace referencia a problemas menores que ocurren con más frecuencia o que pueden ser un poco más complicados de superar para los usuarios. Se les debe dar una baja prioridad y abordarlos en la siguiente versión. |
|   3   |                       Significa problemas importantes que ocurren con frecuencia y que los usuarios no pueden resolver por sí mismos. Es crucial abordarlos y asignarles una alta prioridad.                       |
|   4   |                  Corresponde a problemas muy graves que tienen un gran impacto y que impiden a los usuarios seguir utilizando la herramienta. Es imperativo solucionarlos antes del lanzamiento.                   |

#### TABLA RESUMEN:

| # |                                                  Problema                                                   | Escala de severidad	 |            Heurística/Principio violada(o)            |  
|:-:|:-----------------------------------------------------------------------------------------------------------:|:--------------------:|:-----------------------------------------------------:|
| 1 | El usuario no encuentra la tecla "/" para poder escribir la fecha de nacimiento en la pantalla de registro. |          2           |        Match between system and the real world        |
| 2 |           Ausencia de un indicador para señalar que el campo se debe completar obligatoriamente.            |          2           | Visibility of system status/Consistency and standards |
| 3 |      Falta de visibilidad de los márgenes en la sección para escribir los datos del register y log in.      |          1           |              Visibility of system status              |
| 4 |      Ausencia del botón para las personas que no se identifican con los géneros mostrados en register.      |          2           |                Help and documentation                 |
| 5 |       Ambigüedad en la pantalla del register que se debe poner los dos nombres y/o los dos apellidos.       |          2           |        Match between system and the real world        |
| 6 |                       Ausencia de la funcionalidad del botón “forgot your password?”.                       |          3           |               User control and freedom                |
| 7 |                           Visibilidad de la contraseña en la pantalla de log in.                            |          3           |              Visibility of system status              |             
| 8 |                    Ausencia de la funcionalidad de los botones en la pantalla de log in.                    |          3           |               User control and freedom                |
| 9 |          El FAQ carece de un diseño atractivo y utiliza una tipografía y colores poco atractivos.           |          2           |            Aesthetic and minimalist design            |

**Problema #1:** El usuario no encuentra la tecla "/" para poder escribir la fecha de nacimiento en la pantalla de registro.

**Escala de Severidad:** Nivel 2 (Problema menor).

**Heurística relacionada:**

Heurística #2: Match between system and the real world
La interfaz debe utilizar elementos familiares).

**Descripción del problema:** Los usuarios no pueden encontrar la tecla "/" para ingresar su fecha de nacimiento, lo que puede ser confuso y dificultar la entrada de datos.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/qgvLR9B/Screenshot-2023-11-03-163848.png" alt="Screenshot-2023-11-03-163848" border="0"></a>

**Recomendación:** Colocar la tecla "/" de manera más visible y/o proporcionar una indicación clara de cómo ingresar la fecha de nacimiento.


**Problema #2:** Ausencia de un indicador para señalar que el campo se debe completar obligatoriamente.

**Escala de Severidad:** Nivel 2 (Problema menor).

**Heurística relacionada:**

Heurística #1: Visibility of system status
(Los campos obligatorios deben indicarse claramente).
Heurística #4: Consistency and standards
(El uso de indicadores de campos obligatorios es una práctica común).

**Descripción del problema:** Los usuarios no pueden identificar fácilmente qué campos son obligatorios y cuáles no, lo que puede llevar a errores en la entrada de datos.

<a href="https://ibb.co/tDDttBS"><img src="https://i.ibb.co/cQQHHJP/Screenshot-2023-11-03-163946.png" alt="Screenshot-2023-11-03-163946" border="0"></a>

**Recomendación:** Agregar indicadores claros, como asteriscos o mensajes de ayuda, para indicar campos obligatorios.


**Problema #3:** Falta de visibilidad de los márgenes en la sección para escribir los datos del registro y log in.

**Escala de Severidad:** Nivel 1 (Problema superficial).

**Heurística relacionada:**

Heurística #1: Visibility of system status
(La falta de visibilidad de los márgenes puede ser un problema superficial).

**Descripción del problema:** La falta de visibilidad de los márgenes puede no ser un problema crítico, pero puede afectar la estética y la claridad de la interfaz.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/wryGt6m/Screenshot-2023-11-03-164059.png" alt="Screenshot-2023-11-03-164059" border="0"></a>

**Recomendación:** Mejorar la visibilidad de los márgenes o bordes en la interfaz para una apariencia más ordenada y clara.

**Problema #4:** Ausencia del botón para las personas que no se identifican con los géneros mostrados en register.

**Escala de Severidad:** Nivel 2 (Problema menor).

**Heurística relacionada:**

Heurística #10: Help and documentation
(La inclusión de opciones para diferentes identidades es importante).

**Descripción del problema:** La falta de opciones para personas LGBTQ puede ser excluyente y no reconoce la diversidad de los usuarios.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/n0rYJnm/Screenshot-2023-11-03-163451.png" alt="Screenshot-2023-11-03-163451" border="0"></a>

**Recomendación:** Incluir una opción que permita a las personas identificarse como LGBTQ.


**Problema #5:** Ambigüedad en la pantalla del registro sobre si se deben poner los dos nombres y/o los dos apellidos.

**Escala de Severidad:** Nivel 2 (Problema menor).

**Heurística relacionada:**

Heurística #2: Match between system and the real world
(La claridad en la entrada de datos es importante).

**Descripción del problema:** La ambigüedad en la entrada de nombres y apellidos puede llevar a errores en el registro.

<a href="https://ibb.co/wzR6C7Y"><img src="https://i.ibb.co/71XyVQb/Screenshot-2023-11-03-163355.png" alt="Screenshot-2023-11-03-163355" border="0"></a>

**Recomendación:** Proporcionar instrucciones claras sobre cómo completar los campos de nombres y apellidos.


**Problema #6:** Ausencia de la funcionalidad del botón "forgot your password?".

**Escala de Severidad:** Nivel 3 (Problema mayor).

**Heurística relacionada:**

Heurística #3: User control and freedom
(Los usuarios deben poder recuperar sus contraseñas).

**Descripción del problema:** La falta de una función para restablecer contraseñas puede dejar a los usuarios sin opciones si olvidan su contraseña.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/cbYPkZn/Screenshot-2023-11-03-163235.png" alt="Screenshot-2023-11-03-163235" border="0"></a>

**Recomendación:** Agregar la funcionalidad del botón "Forgot your password?" para permitir a los usuarios restablecer sus contraseñas.


**Problema #7:** Visibilidad de la contraseña en la pantalla de log in.

**Escala de Severidad:** Nivel 3 (Problema menor).

**Heurística relacionada:**

Heurística #1: Visibility of system status
(La visibilidad de la contraseña puede ser un problema menor).

**Descripción del problema:** La visibilidad de la contraseña puede no ser crítica, pero podría afectar la privacidad y seguridad de la información.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/2hT8rth/image.png" alt="image" border="0" /></a>

**Recomendación:** Proporcionar una opción para ocultar/mostrar la contraseña según la preferencia del usuario.


**Problema #8:** Ausencia de la funcionalidad de los botones en la pantalla de log in.

**Escala de Severidad:** Nivel 3 (Problema mayor).

**Heurística relacionada:**

Heurística #3: User control and freedom
(Los botones deben funcionar correctamente).

**Descripción del problema:** La falta de funcionalidad de los botones en la pantalla de inicio de sesión impide a los usuarios acceder a la plataforma.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/dB7nVSL/Screenshot-2023-11-03-163019.png" alt="Screenshot-2023-11-03-163019" border="0"></a>

**Recomendación:** Asegurarse de que los botones funcionen correctamente y permitan a los usuarios iniciar sesión de manera efectiva.


**Problema #9:** El FAQ carece de un diseño atractivo y utiliza una tipografía y colores poco atractivos.

**Escala de Severidad:** Nivel 2 (Problema menor).

**Heurística relacionada:**

Heurística #8: Aesthetic and minimalist design
(El diseño debe ser atractivo y presentar información de manera clara).

**Descripción del problema:** La apariencia del FAQ es poco atractiva debido a la elección de colores, tipografía y diseño general.

<a href="https://ibb.co/cryNQGb"><img src="https://i.ibb.co/rwQZHCb/Screenshot-2023-11-03-162900.png" alt="Screenshot-2023-11-03-162900" border="0"></a>

**Recomendación:** Rediseñar el FAQ para que tenga una apariencia más atractiva y utilice una tipografía y colores que sean más agradables a la vista.

## 5.4. Video About-the-Product.
