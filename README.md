# Proyecto de Uso de JSON-Server para un Pequeño Backend con una Base de Datos NoSQL

Este proyecto es una demostración de cómo utilizar json-server para crear un pequeño backend con una base de datos NoSQL. Json-server es una herramienta que nos permite simular un servidor RESTful utilizando un archivo JSON como base de datos.

![Backend Development](https://cdn.pixabay.com/photo/2016/11/19/17/14/server-1840765_960_720.jpg)

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
