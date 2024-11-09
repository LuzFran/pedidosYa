create table usuario(
  id_usuario serial,
  correo_electronico varchar(100) not null unique check(correo_electronico <> ''),
  contrasenia varchar(50) not null check(contrasenia <>''),
  nombre varchar(50) not null,
  apellido varchar(50) not null,
  fecha_nacimiento date not null check(fecha_nacimiento < current_date),
  telefono varchar(50) no null,
  suscripto_publicidad varchar(2) not null check(suscripto_publicidad in ('Si','No'),
  CONSTRAINT pk_usuario PRIMARY KEY (id_usuario)
);
