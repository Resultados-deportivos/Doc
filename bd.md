# Tablas y Campos en la Base de Datos
## Tabla "Partidos"
* Id (Clave primaria de tipo INT auto incremental)
* Fecha (Tipo DATE)
* Lugar (Tipo VARCHAR de longitud 255)
* EquipoLocalID (Tipo INT)
* EquipoVisitanteID (Tipo INT)
* Jornada (Tipo INT)
## Tabla "Campos"
* Id (Clave primaria de tipo INT auto incremental)
* Ubicacion (Tipo VARCHAR de longitud 255)
* Polideportivo (Tipo VARCHAR de longitud 255)
## Tabla "Registros"
* Id (Clave primaria de tipo INT auto incremental)
* PartidoID (Tipo INT)
* JugadorID (Tipo INT)
* MinutosJugados (Tipo INT)
* PuntosMarcados (Tipo INT)
## Tabla "Usuarios"
* Id (Clave primaria de tipo INT auto incremental)
* Nombre (Tipo VARCHAR de longitud 255)
* Contrasena (Tipo VARCHAR de longitud 255)
* Correo (Tipo VARCHAR de longitud 255)
* Admin (Tipo BOOLEAN)
* Tabla "Acciones"
* AccionID (Clave primaria de tipo INT auto incremental)
* Descripcion (Tipo VARCHAR de longitud 255)
## Tabla "Fechas"
* Fecha (Clave primaria de tipo DATE)
## Tabla "Publicaciones"
* Id (Clave primaria de tipo INT auto incremental)
* Img (Tipo VARCHAR de longitud 255)
* Titulo (Tipo VARCHAR de longitud 255)
* Descripcion (Tipo VARCHAR de longitud 255)
## Tabla "Equipos"
* EquipoID (Clave primaria de tipo INT)
* Nombre (Tipo VARCHAR de longitud 255)
* Ciudad (Tipo VARCHAR de longitud 255)
