1. Diagrama ER (Entidad-Relación)
El diagrama ER incluye las siguientes entidades y relaciones:

Usuario
ID_Usuario (PK)
Nombre
Correo
Teléfono

Ingeniero
ID_Ingeniero (PK)
Nombre
Correo
Experiencia
Capacidad_Actual

Categoría
ID_Categoría (PK)
Nombre

Caso
ID_Caso (PK)
Descripción
Fecha_Apertura
Fecha_Cierre
Estado
ID_Usuario (FK)
ID_Categoría (FK)

Asignación
ID_Asignación (PK)
ID_Caso (FK)
ID_Ingeniero (FK)
Fecha_Asignación

Procedimiento
ID_Procedimiento (PK)
ID_Caso (FK)
Descripción
Fecha_Procedimiento

Calificación
ID_Calificación (PK)
ID_Caso (FK)
Puntuación
Comentarios
