# Capítulo III: Requirements Specification 

## 3.1 To-Be Scenario Mapping

**Segmento: Veterinaria**

| Fase | Necesito Registrar la atención de mascotas | Realizo el proceso de citas | Administro los productos que tengo en disposición para las mascotas |
|-----|--------------|--------------|--------------|
| Doing 	| Ofrezco tips y consejos para tratar en primera instancia un malestar de las mascotas	| Establezco la disponibilidad y el medio para reservar citas a través de la plataforma web 	|Establezco un apartado para poder promocionar los productos en disposición y los precios por medio de la aplicación. |
| 			| Ofrezco los servicios de la veterinaria por medio de la plataforma y sus costos	| Optimizamos el tiempo en reserva de citas con ayuda de la relacion de disponibilidad y el tipo de estructura que desarrollamos para la aplicación web	|	Implementamos un apartado de galería para la venta tanto de medicamentos como de juguetes y alimentos |
| Thinking  | Sentimos satisfacción por enfocar que nuestras presentaciones en la plataforma sean avaladas por personal calificado en las áreas respectivas	|	Priorizamos la utilidad de la plataforma para que nuestros clientes gozen de la mejor experiencia posible|	Se busca administrar y realizar mantenimiento de manera constante a la plataforma para no generar malas experiencias en el usuario |
| 			|	El interfaz para la presentación del registrado de citas es dinámico y fácil de comprender| la conexión del agendado de citas está directamente relacionado con el servidor de la base de datos e razón de no tener inconvenientes en medio del tránsito de información	|	Añado promociones para poder atraer a más clientes con buenos precios |
| Feeling   |Felicidad por el servicio que brindo es de mayor calidad	| Serenidad porque existe un orden que ayuda en la atención de mis clientes y mascotas	|Feliz porque puedo vender más productos sin necesidad de un espacio físico para mostrarlos |


**Segmento: Dueños de mascotas**

| Fase | Necesito atención para mi mascota | Agendo una cita con un veterinario | Compro insumos para mi mascota |
|-----|--------------|--------------|--------------|
| Doing 	|Busco tips en la plataforma con el respaldo de veterinarios profesionales	|Busco en la plataforma las fechas disponibles para agendar una cita	|Busco Productos para mi mascota en la plataforma |
| 			|Reviso los tipos de atención que necesito para mi mascota 	|Ahorré mucho tiempo en agendar la cita ya que la plataforma me ayudó |Encuentro gran variedad de productos para mi mascota desde medicinas hasta juguetes|
| Thinking  |Me siento seguro de los tips que veo en la plataforma ya que son respaldados por veterinarios	|Pienso que la plataforma es una gran herramienta de ayuda	|La tienda virtual es eficaz porque me permite encontrar facilmente los productos de receta medica |
| 			|La atención a mi mascota fue rápida debido a la organización del agendado de citas	|Pienso que esta situación me prevee de llevar a mi mascota a veterinarias que no conozco	|La tienda virtual tiene muchos productos y me ahorro el tiempo de ir a una tienda física |
| Feeling   |Siento que puedo ayudar a mi mascota si hago caso a los consejos que encuentro en la plataforma	|Siento satisfaccion porque puedo atender a mi mascota 	|Siento felicidad porque la plataforma ayuda a encontrar productos variados |
|			|Siento alivio porque sé que podré atender a mi mascota	|Siento satisfaccion de llevar a mi mascota a la veterinaria porque la atención es buena	|Me siento feliz porque encuentro todo tipo de producto para mascotas en la plataforma	|


## 3.2. User Stories

**Segmento: Veterinaria**

| ID    | Título                            | Descripción                                                | Criterios de Aceptación                                      | ID de Épica |
|-------|-----------------------------------|------------------------------------------------------------|--------------------------------------------------------------|------------|
| HUV01 | Programar una Cita para una Mascota | Como veterinario, quiero permitir a los clientes programar citas para sus mascotas de acuerdo con la disponibilidad de los veterinarios. | - Los clientes deben poder seleccionar una fecha y hora disponibles para la cita. - Si no hay disponibilidad en la fecha y hora deseada, los clientes deben recibir una notificación de que deben elegir otra hora. - Los clientes deben poder proporcionar detalles sobre la mascota y el motivo de la cita al programarla. | EP001  |
| HUV02 | Registrar Datos del Paciente     | Como veterinario, quiero poder registrar y mantener actualizada la información de los pacientes y sus dueños. | - Debe haber un formulario para registrar los datos de la mascota, incluyendo nombre, edad, especie, raza y propietario. - Los datos del paciente deben poder actualizarse en cualquier momento, por ejemplo, si hay un cambio de dirección o contacto. - Los registros de pacientes deben estar organizados y accesibles para el personal de la veterinaria. | EP002      |
| HUV03 | Guardar Historial del Paciente    | Como veterinario, quiero poder mantener un historial médico completo de cada paciente para un seguimiento adecuado. | - Debe haber una sección de historial médico para cada paciente, donde se registren las visitas anteriores, diagnósticos, tratamientos y prescripciones. - Los veterinarios deben poder acceder fácilmente al historial de un paciente antes de cada cita. - Los cambios en el historial deben registrarse con fecha y hora. | EP002      |
| HUV04 | Venta de Productos en Línea      | Como veterinario, quiero ofrecer la venta de productos para mascotas en línea para aumentar los ingresos y la comodidad de los clientes. | - Debe haber una tienda en línea con productos para mascotas, incluyendo alimentos, medicamentos, juguetes, etc. - Los clientes deben poder agregar productos a su carrito de compras y proceder al pago en línea. - Debe haber opciones para buscar productos por categoría, marca y precio. | EP003      |
| HUV05 | Brindar Consejos de Cuidado para Mascotas | Como veterinario, quiero ofrecer consejos y guías de cuidado para mascotas a través de la aplicación para educar a los dueños de mascotas. | - La aplicación debe proporcionar una sección de "Consejos para el Cuidado de Mascotas" con artículos y guías. - Los consejos deben estar organizados por categorías, como alimentación, higiene, entrenamiento, etc. - Los usuarios deben poder marcar los consejos como favoritos y compartirlos en redes sociales. | EP003      |
| HUV06 | Gestión de Disponibilidad de Cita | Como administrador de la veterinaria, quiero poder definir y gestionar la disponibilidad de citas para los veterinarios. | - Debe haber una interfaz de administración que permita definir los horarios de trabajo de cada veterinario. - Deben poder bloquearse ciertos horarios para vacaciones o descansos. - La disponibilidad de citas debe actualizarse automáticamente en tiempo real en función de los horarios definidos. | EP001      |
| HUV07 | Generar Reportes de Ventas        | Como dueño de una veterinaria, quiero poder generar informes de ventas para evaluar el rendimiento de la tienda en línea. | - Debe haber una función que permita generar informes de ventas mensuales y anuales. - Los informes deben mostrar los ingresos totales, las categorías de productos más vendidas y otras métricas relevantes. - Los informes deben poder exportarse en formatos como PDF o CSV. | EP003      |

**Segmento: Dueños de mascotas**

| ID    | Título                            | Descripción                                                | Criterios de Aceptación                                      | ID de Épica |
|-------|-----------------------------------|------------------------------------------------------------|--------------------------------------------------------------|------------|
| HUD01 | Reservar una Cita para mi Mascota | Como dueño de una mascota, quiero poder reservar una cita médica en línea para mi mascota. | - Debo poder seleccionar una fecha y hora disponibles para la cita. - Debo poder proporcionar los detalles de mi mascota y el motivo de la cita. - Después de la reserva, debo recibir una confirmación por correo electrónico. | EP001      |
| HUD02 | Comprar Productos para mi Mascota | Como dueño de una mascota, quiero poder comprar productos en línea para mi mascota, como comida, juguetes y accesorios. | - Debo poder buscar y navegar por una variedad de productos para mascotas. - Debo poder agregar productos a mi carrito de compras y proceder al pago. - Debo tener la opción de ingresar la dirección de envío y realizar el pago de forma segura. | EP002      |
| HUD03 | Visualizar Consejos de Cuidado   | Como dueño de una mascota, quiero acceder a consejos de cuidado y educación sobre el bienestar de mi mascota. | - La aplicación debe ofrecer una sección de "Consejos para el Cuidado de Mascotas" donde los usuarios puedan explorar artículos y consejos. - Los consejos deben estar organizados por categorías como alimentación, ejercicio, entrenamiento, etc. - Debo poder marcar los consejos como favoritos para acceder fácilmente a ellos. | EP003      |
| HUD04 | Filtro de Productos por Categoría | Como dueño de una mascota, quiero poder filtrar los productos por categoría para encontrar fácilmente lo que necesito. | - En la sección de compras, debo poder seleccionar una categoría (por ejemplo, comida, juguetes, accesorios) para ver productos específicos. - Los productos mostrados deben coincidir con la categoría seleccionada. - Debo tener la opción de borrar el filtro y volver a ver todos los productos. | EP002      |
| HUD05 | Recibir Recordatorio de Cita     | Como dueño de una mascota, quiero recibir un recordatorio automático dos días antes de una cita médica programada para mi mascota. | - Debo poder programar citas médicas en línea y proporcionar la fecha y hora de la cita. - El sistema debe enviar automáticamente un recordatorio por correo electrónico o notificación dos días antes de la cita programada. - Debo poder ver y modificar la fecha de la próxima cita en mi perfil. | EP001      |
| HUD06 | Comentarios y Calificaciones     | Como dueño de una mascota, quiero poder ver los comentarios y calificaciones de otros usuarios sobre los productos antes de comprarlos. | - Debo poder ver los comentarios y calificaciones de otros usuarios en la página de detalles del producto. - Debe haber un sistema de calificación por estrellas y la opción de dejar comentarios. - Los comentarios deben mostrar la fecha de publicación y el nombre del usuario que los dejó. | EP002      |
| HUD07 | Acceder a Guías de Cuidado       | Como dueño de una mascota, quiero acceder a guías detalladas de cuidado y salud para mi tipo específico de mascota (perro, gato, pájaro, etc.). | - La aplicación debe ofrecer guías de cuidado específicas para diferentes tipos de mascotas. - Debo poder seleccionar mi tipo de mascota y acceder a información relevante. - Las guías deben ser informativas y proporcionar consejos útiles sobre el cuidado y la salud de la mascota. | EP003      |

## 3.3. Impact Mapping

![Impact Mapping](/assets/img/Chapter-III/Impact-Map.png)

## 3.4. Product Backlog

| Número de Orden | ID    | Descripción                                                | Story Points |
|-----------------|-------|------------------------------------------------------------|--------------|
| 1               | vHU001 | Como veterinario, quiero permitir a los clientes programar citas para sus mascotas de acuerdo con la disponibilidad de los veterinarios. | 5            |
| 2               | dHU001 | Como dueño de una mascota, quiero poder reservar una cita médica en línea para mi mascota. | 5            |
| 3               | vHU002 | Como veterinario, quiero poder registrar y mantener actualizada la información de los pacientes y sus dueños. | 3            |
| 4               | dHU002 | Como dueño de una mascota, quiero poder comprar productos en línea para mi mascota, como comida, juguetes y accesorios. | 5            |
| 5               | vHU003 | Como veterinario, quiero poder mantener un historial médico completo de cada paciente para un seguimiento adecuado. | 3            |
| 6               | dHU003 | Como dueño de una mascota, quiero acceder a consejos de cuidado y educación sobre el bienestar de mi mascota. | 2            |
| 7               | vHU004 | Como veterinario, quiero ofrecer la venta de productos para mascotas en línea para aumentar los ingresos y la comodidad de los clientes. | 5            |
| 8               | dHU004 | Como dueño de una mascota, quiero poder filtrar los productos por categoría para encontrar fácilmente lo que necesito. | 3            |
| 9               | vHU005 | Como veterinario, quiero ofrecer consejos y guías de cuidado para mascotas a través de la aplicación para educar a los dueños de mascotas. | 3            |
| 10              | dHU005 | Como dueño de una mascota, quiero recibir un recordatorio automático dos días antes de una cita médica programada para mi mascota. | 2            |
| 11              | vHU006 | Como administrador de la veterinaria, quiero poder definir y gestionar la disponibilidad de citas para los veterinarios. | 5            |
| 12              | dHU006 | Como dueño de una mascota, quiero poder ver los comentarios y calificaciones de otros usuarios sobre los productos antes de comprarlos. | 3            |
| 13              | vHU007 | Como dueño de una veterinaria, quiero poder generar informes de ventas para evaluar el rendimiento de la tienda en línea. | 5            |
| 14              | dHU007 | Como dueño de una mascota, quiero acceder a guías detalladas de cuidado y salud para mi tipo específico de mascota (perro, gato, pájaro, etc.). | 3            |