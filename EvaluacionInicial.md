# Evaluación inicial

El centro de estudios de personas adultas realiza una evaluación inicial de alumnos todos lo inicios de curso.

En esta evaluación se toman los datos de los alumnos que van a dar de alta en el centro. Pero antes de darlos de alta hay que comprobar que hayan estado matriculados previamente. Si estaba matriculado previamente se deben rescatar todos los datos del usuario y se les asigna al curso que deben acceder.
De cada alumno se necesita el nombre, apellidos, dirección, teléfono, DNI/NIE y saber si ha estado matriculado anteriormente en el centro. 
Todos los años hay problemas en la matriculación ya que hay alumnos que se les ha otorgado el DNI y ya no poseen NIE, pero son la misma persona, por lo que hay que tener en cuenta que no podemos poner como elemento diferenciador el DNI del alumno, ya que a lo largo de la vida de los datos estos pueden cambiar.
De cada alumno se almacena a qué curso está matriculado, y en qué año estuvo matriculado.
Los cursos, que pueden ser primero de la ESO, segundo ESO, educación vial, etc tienen asociados grupos por cada año. Así en el curso 21/22 hay grupos de 1ºESO A, 1ª ESO B, etc. Y cada año pueden cambiar.

Cada grupo tiene un cupo máximo de alumnos que se van dando de alta de forma consecutiva. El primero que se matricula, ocupa el primer puesto y así hasta que se agote el cupo. A partir de ese momento los alumnos se apuntan pero en lista de espera, y no deben perder el orden de acceso. 
En el momento de la matriculación el alumno debe saber si está matriculado o está en lista de espera.
Las matriculaciones las realizan profesores del ciclo. Un profesor se autentica contra la plataforma y se le debe aparecer un formulario para comenzar la matriculacion.

El adminstrador de la plataforma podrá obtener en cualquier momento listado de en qué situación se encuentra un grupo de clase, con el listado de los alumnos, en qué posición se encuentra, y si está en lista de espera o matriculado.

El administrador al finalizar la jornada de matriculación, obtendrá un informe organizado por profesores, donde aparecera el número de alumnos que ha atendido. 

## Listados

Los listados que se deben obtener de la plataforma son:

### Listado por grupo

**Grupo 1ªESO-A**

| NºOrden | Nombre   |
|---------|----------|
| 1       | Alumno 1 |
| 2       | Alumno 2 |
| ...     |          |
| Reserva | Alumno n |

### Listado de grupos

|   Grupo  | Max Matriculados | Matriculados | Lista de espera |
|:--------:|:----------------:|:------------:|:---------------:|
| ESO 1º A |        25        |      30      |        5        |
| ESO 1º B |        25        |      12      |        0        |

### Listado de alumnos

|  Alumno  |   Grupo  |
|:--------:|:--------:|
| Alumno 1 | ESO 1º A |
| Alumno 2 | ESO 2º C |
|    ...   |    ...   |

### Informe de matriculaciones

|  Profesor  | Nº alumnos matriculados |
|:----------:|:-----------------------:|
| Profesor 1 |            23           |
| Profesor 2 |            22           |