# API REST Testing con Postman

Proyecto de pruebas automatizadas para practicar el testing de una API REST utilizando **Postman** y **JavaScript**.

La API utilizada en este proyecto es **JSONPlaceholder**.

## 🧪 Pruebas realizadas

El flujo de pruebas incluye tres operaciones principales:

### POST - Crear un recurso

Se envía una petición `POST` para crear una nueva publicación.

Se comprueba:

* Que la petición se envía correctamente.
* Que la respuesta devuelve `201 Created`.
* Que los datos enviados aparecen en la respuesta.
* Se guarda el ID del recurso creado para utilizarlo posteriormente.

### GET - Consultar un recurso

Se realiza una petición `GET` utilizando el ID obtenido en el paso anterior.

Se comprueba:

* Que la respuesta devuelve `200 OK`.
* Que el recurso contiene la información esperada.
* Que los datos recibidos son correctos.

### DELETE - Eliminar un recurso

Se envía una petición `DELETE` utilizando el mismo ID.

Se comprueba:

* Que la petición se procesa correctamente.
* Que la respuesta devuelve `200 OK`.

## 🛠️ Tecnologías utilizadas

* **Postman** — creación y ejecución de las pruebas.
* **JavaScript** — automatización de las validaciones.
* **JSON** — intercambio de datos.
* **JSONPlaceholder** — API utilizada para las pruebas.

## 📂 Archivos

```text
API-Testing-Postman/
│
├── README.md
└── API-Testing-Postman.json
```

## ▶️ Cómo ejecutar las pruebas

1. Descargar el archivo `API-Testing-Postman.json`.
2. Abrir Postman.
3. Seleccionar **Import** y cargar el archivo.
4. Abrir la colección importada.
5. Ejecutar las pruebas desde **Run Collection** o **Collection Runner**.

## ✅ Resultado esperado

Las tres peticiones deben ejecutarse correctamente y las validaciones configuradas en los **Post-response Scripts** deben aparecer como **Passed** en Postman.
