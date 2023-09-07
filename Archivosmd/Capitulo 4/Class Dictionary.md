CLASE PERSONA
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|VARCHAR(10)|SI|En este atributo se guarda el código del cliente y sirve como identificador de latabla PERSONA. Se comporta como PRIMARY KEY para comunicar la clase con la clase MASCOTA|
|NOMBRE|VARCHAR(100)|NO|En este atributo se guarda el nombre del cliente, dueño de la mascota|
|APELLIDO|VARCHAR(100)|NO|En este atributo se guarda el apellido del cliente, dueño de la mascota|
|TELEFONO|NUMBER(9)|NO|En este atributo se guarda el telefono del cliente, dueño de la mascota|
|DOMICILIO|VARCHAR(200)|NO|En este atributo se guarda la dirección del domicilio del cliente, dueño de la mascota|
|ESTADO|CHAR(1)|NO|En este atributo se guarda el estado del cliente respecto a la atención en la veterinaria entre activo (A) e inactivo (I)|


CLASE MASCOTA
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|VARCHAR(10)|SI|En este atributo se guarda el código de la mascota, que se genera al ser registrado por primera vez en la veterinaria|
|NOMBRE|VARCHAR(100)|NO|En este atributo se guarda el nombre completo de la mascota|
|EDAD|NUMBER(3)|NO|En este atributo se guarda la edad de la mascota|
|FECHANAC|DATE|NO|En este atributo la fecha de nacimiento de la mascota|
|RAZA|VARCHAR(100)|NO|En este atributo se guarda la raza de la mascota|

CLASE HISTORIAL MEDICO
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|VARCHAR(10)|SI|En este atributo se guarda el codigo de una intervención del historial médico de la mascota, se comporta como identificador de la clase|
|DIAGNOSTICO|VARCHAR(500)|NO|En este atributo se almacena el diagnóstico que recibió la mascota en la intervención, si es que hubiera|
|RECETA|VARCHAR(500)|NO|En este atributo se almacena la información de los medicamentos recetados para la macota|
|ATENCION|VARCHAR(500)|NO|En este atributo se almacena la atención que recibió la mascota al ser intervenida|
|ESTADO|CHAR(1)|NO|En este atributo se almacena el estado en el que se encuentra el padecimiento o el servicio, si activo(A) o inactivo(I) |

CLASE VETERINARIA
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|ID_VET|VARCHAR(8)|SI|En este atributo se almacena el código de la veterinaria, se comporta como identificador de la clase|
|NOMBRE|VARCHAR(100)|NO|En este atributo se almacena el nombre de la Veterinaria|
|DIRECCION|VARCHAR(150)|NO|En este atributo se almacena la dirección de la sede de la Veterinaria|

CLASE DOCTOR
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|VARCHAR(10)|SI|En este atributo se almacena el codigo del médico-veterinario que trabaja en la Veterinaria, se comporta como identificador de la clase|
|NOMBRE|VARCHAR(100)|NO|En este atributo se almacena el nombre del médico-veterinario|
|APELLIDO|VARCHAR(100)|NO|En este atributo se almacena el apellido del médico-veterinario|
|EDAD|NUMBER(2)|NO|En este atributo se almacena la edad del médico-veterinario|
|PROFESION|VARCHAR(150)|NO|En este atributo se almacena la profesión del médico-veterinario|
|TELEFONO|NUMBER(9)|NO|En este atributo se almacena el número de teléfono celular del médico-veterinario|
|DOMICILIO|VARCHAR(200)|NO|En este atributo se almacena el domicilio del médico-veterinario|


CLASE CITAS
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|CHAR(10)|SI|En este atributo se guardan los cóodigos de las citas disponibles |
|FECHA|DATE|NO||
|HORA|NUMBER(2)|NO||
|MINUTO|NUMBER(2)|NO||
|TIPO_CITA|VARCHAR(200)|NO||
|ESTADO|CHAR(1)|NO||
