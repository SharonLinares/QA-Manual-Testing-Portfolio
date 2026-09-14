# API Testing con Postman

Proyecto de pruebas automatizadas para validar una API REST usando Postman y JavaScript.

## Pruebas realizadas

* **POST:** creación de una publicación y validación del código `201 Created`.
* **GET:** consulta de la publicación y validación del código `200 OK` y de su contenido.
* **DELETE:** eliminación de la publicación y validación del código `200 OK`.

El ID generado en el `POST` se guarda para utilizarlo en las siguientes peticiones.

## Herramientas

* **Postman**
* **JavaScript**
* **JSONPlaceholder**

## Cómo ejecutar

1. Descarga el archivo `.json` del repositorio.
2. Impórtalo en Postman desde **Import*.
3. Ejecuta la colección con **Collection Runner**.
