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

![Repository Created](/assets/img/Chapter-V/Repository-Landing.png)

Una vez creado nuestro repositorio, nos repartimos las distintas user stories para el desarrollo de nuestra landing page y creamos las ramas necesarias para que cada integrante pueda trabajar sin complicaciones.

![Branches](/assets/img/Chapter-V/Branches.png)

En el apartado de build and deployment selecciónamos la rama que queremos que se despliegue, en nuestro caso sería la rama develop, en la cual se realizan todos los cambios.

![Github pages used](/assets/img/Chapter-V/Github-Pages-Config.png)

Le damos a guardar y empezaría el despliegue de nuestro landing en Github Pages, nos generará un link con el cual podemos acceder a nuestro landing page.

![Landing Page image](/assets/img/Chapter-V/Landing-Page.png)

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

![Landing 1](/assets/img/Chapter-V/Landing-Page.png)

![Landing 2](/assets/img/Chapter-V/Landing-Page-About.png)

![Landing 3](/assets/img/Chapter-V/Landing-Page-Recommendation.png)

![Landing 4](/assets/img/Chapter-V/Landing-Page-Faq.png)

![Landing 5](/assets/img/Chapter-V/Landing-Page-Pet.png)

### 5.2.1.5.  Software Deployment Evidence for Sprint Review.
Para la implementación de nuestra página, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "main" que previamente se encontrba en la rama develop.

**Link de la Landing Page desplegada:**  https://upc-coders.github.io/MapVet-LandingPage/
### 5.2.1.6. Team Collaboration Insights during Sprint.
En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo

![commits-1](/assets/img/Chapter-V/gitflow-pulse.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo.

![commits-2](/assets/img/Chapter-V/gitflow-traffic.png)

Estos gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![network](/assets/img/Chapter-V/gitflow-network.png)

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

![Paginaweb-landing](/assets/img/Chapter-V/landingpage.jpeg)

![Paginaweb-vets](/assets/img/Chapter-V/veterinarias.jpeg)

![Paginaweb-vets2](/assets/img/Chapter-V/veterinarias2.jpeg)

![Paginaweb-appoinments](/assets/img/Chapter-V/appoinments.jpeg)

![Paginaweb-faq](/assets/img/Chapter-V/faq.jpeg)

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el segundo sprint, hemos logrado un progreso sustancial en la documentación de nuestros servicios web. Hemos documentado varios puntos de acceso (Endpoints) que son esenciales para el funcionamiento de nuestra aplicación. A continuación, proporcionamos detalles sobre los puntos de acceso documentados, ejemplos de interacción y enlaces a la documentación desplegada.

Repositorio: https://github.com/upc-coders/Frontend-MapVet/tree/develop

![Commmits](/assets/img/Chapter-V/commits.png)

**Endpoints Documentados**

|  Endpoint	   | Verbo HTTP  | Parámetros | Ejemplo de Llamada |                              
|:------------:|:-------------------:|:----------:|:------------------:|
| /appoinment  |     GET      |  Ninguno   | GET<br/>/tutorials |
|    /data     |     GET      |  Ninguno   |    GET<br/>/faq    |


### 5.2.2.7.  Software Deployment Evidence for Sprint Review.

Para la implementación de nuestra página, optamos por utilizar GitHub para el control de versiones y colaboración en equipo. En este proceso, creamos un repositorio donde a partir de ramas colaboramos cada integrante del equipo, al finalizar pasamos todo a la rama develop. Netlify fue la plataforma que utilizamos para el despliegue de la página web.

Enlace de la pagina web: https://vetmap.netlify.app/

![Paginaweb-landing-desplegado](/assets/img/Chapter-V/landing-despliegue.png)

![Paginaweb-vets-desplegado](/assets/img/Chapter-V/vet-despliegue.png)

![Paginaweb-appoinments-desplegado](/assets/img/Chapter-V/appoinment-despliegue.png)

![Paginaweb-faq-desplegado](/assets/img/Chapter-V/faq-desplieque.png)

### 5.2.2.8. Team Collaboration Insights during Sprint.

En el segundo sprint, nuestro equipo se enfocó en la implementación del frontend y la revisión y mejora del informe. Utilizamos la metodología Gitflow y seguimos un formato Markdown para la colaboración, y los cinco miembros del equipo participaron de manera efectiva. Durante este período, se llevaron a cabo las tareas de desarrollo del frontend y se realizaron las correcciones necesarias en el informe y la página de inicio.

Imagenes de los commits para el reporte

![Commmits-report](/assets/img/Chapter-V/commits-report.png)

Imagenes de los commits del frontend

![Commmits](/assets/img/Chapter-V/commits.png)

Imagenes de los commits del landing page

![Commmits-Landing](/assets/img/Chapter-V/commits-landing.png)


## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Información personal:**
-	¿Cuál es tu nombre?
-	¿Cuál es tu edad?
-	¿Cuál es tu estado social?
-	¿Cuál es tu ocupación profesional?
-	¿Te encuentras trabajando en la actualidad?

**Preguntas de interacción con la Landing Page y Web Application:**
-	¿Como se sintió al interactuar con el landing page?
-	¿Y en el apartado de la aplicación web, como sintió al interactuar con esta?
-	¿Cómo fue su experiencia con el menú y botones tanto en el landing page como con la aplicación web?
-	¿Logra identificar fácilmente las secciones importantes, como títulos y botones en las distintas vistas de la aplicación y en el Landing Page?
-	¿Considera que la información brindada es puntual y sencilla?
-	¿Siente que las tareas de reservar una cita y usar el mapa serian sencillas de realizar usando la interfaz?
-	¿Pudo visualizar correctamente los perfiles de las mascotas y el mapa?



### 5.3.2. Registro de Entrevistas.

### 5.3.3. Evaluaciones según heurísticas.

## 5.4. Video About-the-Product.