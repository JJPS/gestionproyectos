# Gestión de Payloads

Eres un hacker que necesitar organizar los payloads que se generan, los payloads no son más que archivos que se pueden subir y bajar de un servidor.
Nuestra web va a tener dos funcionalidades:

## Primera: Gestion de payloads

Se podrán almacenar de forma organizada los payloads, y poder gestionar en qué categoría puedo almacenarlos. 

Así que tendremos una base de datos que deberá almacenar el nombre del payload, a qué categoría va asociado, un número de payload y el fichero del payload. Que normalmente es un fichero de texto con una extensión de tipo .sh o .bat

Las categorías se deberán almacenar en una tabla ya que puedo agregar categorías en cualquier momento.

Por tanto deberé tener un CRUD de payloads y un CRUD de categorías.

Podre obtener un listado filtrado por nombre o por categoría de payloads con el siguiente contenido: 

**Listados**

| Codigo |        Payload       | Categoria |
|:------:|:--------------------:|:---------:|
|  0001  |  Reverse shell bash  |   Linux   |
|  0002  | Reverse power shell  |  Windows  |
|  0003  |  Reverse shell nano  |   Linux   |
|   ...  |          ...         |    ...    |

## Segunda: Servidor de archivos HTTP. 

El servidor va a poder enviar a través de la ruta html. 

Una petición del tipo:

```
http://servidor.payload.org/payload.php?2342
```

El navegador me descargará el payload con el número de registro 2342, en caso que no exista me mostrará por pantalla un listado con los payloads disponibles agrupados por categoría


