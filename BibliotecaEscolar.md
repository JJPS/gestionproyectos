# Biblioteca Escolar

Un centro de estudios quiere gestionar los libros de su biblioteca, para ello nos encarga una aplicación WEB que, además de gestionar los fondos, gestionar los préstamos.

De un libro necesitamos almacenar su nombre, autor o autores, ISBN, título, tema, curso, ubicación y breve resumen y si el libro está fotocopiado o es original.

Cada libro tiene un tema principal, y un curso asociado. Los temas, los cursos y la ubicación, se gestionarán como tablas maestras.

Los libros pueden ser prestados a profesores o a alumnos. Por lo que deberemos mantener una base de datos de alumnos y profesores que contendrán, nombre, apellidos, correo electrónico, teléfono y si es alumno o profesor. 

Un profesor puede tener prestado un número indeterminado de libros. Un alumno puede tener prestado un máximo de 3 libros. 

En cualquier momento se puede obtener un listado de los libros que tiene prestada una persona y un listado de los libros prestados y qué personal los ha retirado y en qué fecha.

Además del proceso de préstamo se debe tener un proceso de devolución de libros. Ambos procesos deben tener su propio formulario.

Tendremos tres roles en la aplicación:

- Alumno: Un alumno puede hacer una búsqueda de los libros de la biblioteca, y dar de alta una alarma de un libro prestado. Cuándo este se devuelva al alumno se le notificará que ese libro está disponible para el préstamo.

- Profesor: Además de lo anterior, podrá realizar préstamos para si mismo y para cualquier alumno. Además de hacer préstamos podrá realizar devoluciones de libros de cualquier usuario de la misma. El proceso de préstamo y devolución se debe almacenar la persona que realiza la gestión de préstamo o devolución. 

- Administrador: Además de lo anterior, podrá realizar préstamos para cualquier usuario. Es el encargado de gestionar los fondos de la biblioteca (libros), los puede dar de alta, editar, listar, y dar de baja. El proceso de baja de un libro no lo borra, sino que no permite su préstamo puesto que ya no existe, pero se quiere conservar un hístorico de su uso. Gestionar a alumnos y profesores. CRUD.

