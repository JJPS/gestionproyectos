# Gestión de almacen

Una empresa quiere gestionar su stock de almacen, y nos ha contratado para realizar un software que pueda ser usado tanto en PC como en Móvil.

Debemos gestionar las entradas de material y las salidas de material. Cada vez que tengamos una entrada o una salida de almacen se generará un documento que contendrá las referencias que se sacan del almacén y qué persona realiza la gestión de entrada o salida.

De los materiales que queremos gestionar guardaremos su nombre, su código, su familia y el stock actual del almacen. Se deberá ver un histórico de los últimos 10 movimientos de ese producto en pantalla.

La Famlia de productos es una forma de organziar los contenidos, para que cuando se obtengan listados podamos ordenar por familia y dentro de la familia ordenar alfabeticamente los productos.

Los administradores podrán gestionar todo lo relacionado con las tablas maestras: CRUD de Familias, CRUD de Trabajadores, CRUD de Artículos, y gestión de entradas y salidas.

Los trabajdores tendrán dos roles. O son administradores, o son usuarios del sistema. 

Cualquier usuario puede sacar material del almacen. Cada vez que se saque material del almacen se guardará información relacionada con esa extracción como el nombre del usuario, fecha, material que se saca y cantidad de material que sacamos. Este información se puede imprimir en cualquier momento simplemente poniendo el número de salida. 

Solo los administradores pueden dar de alta productos en el almacen. Un usuario puede tener dos roles, y dependiendo del rol que tenga podrá sacar material o meter material. 

En cualquier momento se puede obtener un listado de material, usuarios o familias por impresora, con todos los elementos o con los elementos que aparezcan filtrados en pantalla.


