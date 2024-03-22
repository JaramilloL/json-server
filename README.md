# Proyecto de Uso de JSON-Server para un Pequeño Backend con una Base de Datos NoSQL

Este proyecto es una demostración de cómo utilizar json-server para crear un pequeño backend con una base de datos NoSQL. Json-server es una herramienta que nos permite simular un servidor RESTful utilizando un archivo JSON como base de datos.

![Backend Development]([https://cdn.pixabay.com/photo/2016/11/19/17/14/server-1840765_960_720.jpg](https://www.bing.com/images/search?view=detailV2&ccid=HOCmWGXy&id=CB4AD17A653319C5F685F200676A599EC5388543&thid=OIP.HOCmWGXyfD4F04xFtZyw6gAAAA&mediaurl=https%3a%2f%2fwww.azulschool.net%2fwp-content%2fuploads%2f2020%2f05%2fBackend-Developer-1024x768.png&cdnurl=https%3a%2f%2fth.bing.com%2fth%2fid%2fR.1ce0a65865f27c3e05d38c45b59cb0ea%3frik%3dQ4U4xZ5ZamcA8g%26pid%3dImgRaw%26r%3d0&exph=355&expw=474&q=imagen+de+un+desaroollo+backen&simid=608052226060414690&FORM=IRPRST&ck=7EC4337D123E9324D7E4F7CC630C21F3&selectedIndex=3&itb=0))

## Requisitos

Antes de comenzar, asegúrate de tener instalado Node.js en tu sistema. Puedes descargarlo desde [aquí](https://nodejs.org/).

## Instalación

1. Clona este repositorio en tu máquina local utilizando el siguiente comando: git clone <URL del repositorio>


2. Navega hasta el directorio del proyecto: cd nombre_del_proyecto


3. Instala las dependencias del proyecto utilizando npm: npm install, npm i json-server


## Uso

Para ejecutar el servidor json, simplemente ejecuta el siguiente comando: npm i start


Esto iniciará el servidor en el puerto 3000 por defecto. Puedes acceder a los datos utilizando las rutas RESTful estándar, como `GET`, `POST`, `PUT` y `DELETE`. Por ejemplo:

- `GET /usuarios`: Obtiene todos los usuarios.
- `GET /usuarios/:id`: Obtiene un usuario específico por su ID.
- `POST /usuarios`: Crea un nuevo usuario.
- `PUT /usuarios/:id`: Actualiza un usuario existente.
- `DELETE /usuarios/:id`: Elimina un usuario por su ID.

Recuerda modificar el archivo `db.json` para agregar más datos o cambiar la estructura de la base de datos.

## Contribuir

Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama para tu funcionalidad (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commits explicativos (`git commit -am 'Añade una nueva funcionalidad'`).
4. Sube tus cambios a tu repositorio fork (`git push origin feature/nueva-funcionalidad`).
5. Crea un nuevo Pull Request.

## Créditos

Este proyecto ha sido creado por [tu_nombre].

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
