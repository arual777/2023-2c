#  Clase-6-Practica Entity Framework "Isla del Tesoro"

## En Clase
Hicimos ejemplos Alta, Baja, Modificacion y Listado de la entidad "Tesoro" usando web api y creamos tests usando database in memory

## Modelo de datos
Tesoro
- [Id] [int] IDENTITY(1,1) NOT NULL,
- Nombre VARCHAR(255),
- Descripcion VARCHAR(255),
- ImagenUrl VARCHAR(1000),
- Ubicacion INT NULL,
- Valor DECIMAL(10, 2)
);

## Utilizamos:
- Proyecto de MVC
- Proyecto de Biblioteca de clases
- Entity Framework Core

## Tarea - Agregar "Ubicacion"
- Crear Tabla "Ubicacion" (Id, Nombre)
- Crear script de datos iniciales
- Agregar las operaciones de Alta, Baja, Modificacion y Listado de la entidad "Ubicacion"
- Agregar Tests para todas las operaciones con la entidad Ubicacion
