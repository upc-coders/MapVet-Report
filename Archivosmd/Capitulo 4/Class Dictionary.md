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
|CODIGO|VARCHAR(10)|SI||
|DIAGNOSTICO|VARCHAR(500)|NO||
|RECETA|VARCHAR(500)|NO||
|ATENCION|VARCHAR(500)|NO||
|ESTADO|CHAR(1)|NO||

CLASE VETERINARIA
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|ID_VET|VARCHAR(8)|SI||
|NOMBRE|VARCHAR(100)|NO||
|DIRECCION|VARCHAR(150)|NO||

CLASE PERSONA
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|VARCHAR(10)|SI||
|NOMBRE|VARCHAR(100)|NO||
|APELLIDO|VARCHAR(100)|NO||
|EDAD|NUMBER(2)|NO||
|PROFESION|VARCHAR(150)|NO||
|TELEFONO|NUMBER(9)|NO||
|DOMICILIO|VARCHAR(200)|NO||


CLASE CITAS
|ATRIBUTO|TIPO DE DATO|PRIMARY KEY|DESCRIPCION|
|---|---|---|---|
|CODIGO|CHAR(10)|SI||
|FECHA|DATE|NO||
|HORA|NUMBER(2)|NO||
|MINUTO|NUMBER(2)|NO||
|TIPO_CITA|VARCHAR(200)|NO||
|ESTADO|CHAR(1)|NO||
