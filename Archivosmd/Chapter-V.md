## 5.1.1.	Software Development Environment Configuration.
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

## 5.1.2.	Source Code Management.
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

## 5.1.3.	Source Code Style Guide & Conventions.
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
