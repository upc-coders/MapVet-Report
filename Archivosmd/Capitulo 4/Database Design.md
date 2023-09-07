# DATABASE DESIGN


CREATE TABLE citas (

    codigo    CHAR(10) NOT NULL,
    
    fecha     DATE,
    
    hora      NUMBER(2),
    
    minuto    NUMBER(2),
    
    tipo_cita VARCHAR2(200 BYTE),
    
    estado    CHAR(1 BYTE),
    
    doctor    CHAR(8 BYTE) NOT NULL
    
);

ALTER TABLE citas ADD CONSTRAINT citas_pk PRIMARY KEY ( codigo );

CREATE TABLE doctor (

    codigo    CHAR(8 BYTE) NOT NULL,
    
    nombre    VARCHAR2(100 BYTE),
    
    apellido  VARCHAR2(100 BYTE),
    
    edad      NUMBER(2),
    
    profesion VARCHAR2(150 BYTE),
    
    telefono  NUMBER(9),
    
    domicilio VARCHAR2(200 BYTE)
    
);

ALTER TABLE doctor ADD CONSTRAINT doctor_pk PRIMARY KEY ( codigo );

CREATE TABLE historial_medico (

    codigo      CHAR(10 BYTE) NOT NULL,
    
    diagnostico VARCHAR2(500 BYTE),
    
    receta      VARCHAR2(500 BYTE),
    
    atencion    VARCHAR2(500 BYTE),
    
    estado      CHAR(1 BYTE),
    
    mascota     VARCHAR2(10 BYTE) NOT NULL
    
);

ALTER TABLE historial_medico ADD CONSTRAINT historial_medico_pk PRIMARY KEY ( codigo );

CREATE TABLE mascota (

    codigo      VARCHAR2(10 BYTE) NOT NULL,
    
    nombre      VARCHAR2(100 BYTE),
    
    edad        NUMBER(3),
    
    raza        VARCHAR2(100 BYTE),
    
    dueño       VARCHAR2(10 BYTE) NOT NULL,
    
    veterinaria CHAR(8 BYTE) NOT NULL
    
);

ALTER TABLE mascota ADD CONSTRAINT mascota_pk PRIMARY KEY ( codigo );

CREATE TABLE persona (

    codigo    VARCHAR2(10 BYTE) NOT NULL,
    
    nombre    VARCHAR2(100 BYTE),
    
    apellido  VARCHAR2(100 BYTE),
    
    telefono  NUMBER(9),
    
    domicilio VARCHAR2(200 BYTE),
    
    estado    CHAR(1)
    
);

ALTER TABLE persona ADD CONSTRAINT persona_pk PRIMARY KEY ( codigo );

CREATE TABLE registro_citas (

    mascota VARCHAR2(10 BYTE) NOT NULL,
    
    citas   CHAR(10) NOT NULL,
    
    codigo  CHAR(10 BYTE) NOT NULL
    
);

ALTER TABLE registro_citas ADD CONSTRAINT relation_5_pk PRIMARY KEY ( codigo );

CREATE TABLE veterinaria (

    id_vet    CHAR(8 BYTE) NOT NULL,
    
    nombre    VARCHAR2(100 BYTE),
    
    direccion VARCHAR2(150 BYTE)
    
);

ALTER TABLE veterinaria ADD CONSTRAINT veterinaria_pk PRIMARY KEY ( id_vet );

ALTER TABLE citas

    ADD CONSTRAINT citas_doctor_fk FOREIGN KEY ( doctor )
    
        REFERENCES doctor ( codigo );

ALTER TABLE historial_medico

    ADD CONSTRAINT historial_medico_mascota_fk FOREIGN KEY ( mascota )
    
        REFERENCES mascota ( codigo );

ALTER TABLE mascota

    ADD CONSTRAINT mascota_persona_fk FOREIGN KEY ( dueño )
    
        REFERENCES persona ( codigo );
        

ALTER TABLE mascota

    ADD CONSTRAINT mascota_veterinaria_fk FOREIGN KEY ( veterinaria )
    
        REFERENCES veterinaria ( id_vet );
        

ALTER TABLE registro_citas

    ADD CONSTRAINT relation_5_citas_fk FOREIGN KEY ( citas )
    
        REFERENCES citas ( codigo );

ALTER TABLE registro_citas

    ADD CONSTRAINT relation_5_mascota_fk FOREIGN KEY ( mascota )
    
        REFERENCES mascota ( codigo );





