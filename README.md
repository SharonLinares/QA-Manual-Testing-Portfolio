# API Testing con Postman

Proyecto de pruebas automatizadas de una API REST utilizando Postman y JavaScript.

En este proyecto se prueba un flujo básico de creación, consulta y eliminación de publicaciones utilizando la API JSONPlaceholder.

## Pruebas realizadas

### POST - Crear publicación

Se crea una nueva publicación enviando los datos en formato JSON.

Se valida:

* Código de respuesta `201 Created`
* Datos de la respuesta
* ID generado por la API

El ID obtenido se guarda para utilizarlo en las siguientes peticiones.

### GET - Consultar publicación

Se consulta la publicación creada utilizando el ID obtenido anteriormente.

Se valida:

* Código de respuesta `200 OK`
* Contenido de la respuesta
* Datos de la publicación

### DELETE - Eliminar publicación

Se elimina la publicación utilizando el mismo ID.

Se valida:

* Código de respuesta `200 OK`
* Respuesta de la API

## Herramientas utilizadas

* Postman
* JavaScript
* JSONPlaceholder

## Cómo ejecutar las pruebas

1. Descargar el archivo `API-Testing-Postman.json`.
2. Abrir Postman, importar el archivo JSON descargado, seleccionar la colección y ejecutarla con el Collection Runner.

