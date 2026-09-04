# Explorador de Películas y Series

## Descripción del proyecto

Este proyecto consiste en desarrollar una aplicación web para explorar información sobre películas y series. La aplicación permitirá consultar contenido mediante una API externa, visualizar información relevante y organizar los resultados de una manera sencilla y amigable para el usuario.

El proyecto se desarrollará utilizando React con Vite para el frontend y se contempla una estructura de backend que permita organizar las rutas, controladores, servicios, modelos, middleware y conexión con la base de datos.

Como API principal se utilizará **The Movie Database (TMDB)**, debido a que proporciona información sobre películas, series, actores, imágenes y otros datos relacionados con contenido audiovisual.

## Tecnologías

* React
* Vite
* JavaScript
* HTML5
* CSS
* Node.js
* Express
* API de TMDB
* Git y GitHub

## Estructura del proyecto

### Frontend

La carpeta `src` contiene la aplicación React y está organizada de la siguiente manera:

* `components/` — Componentes reutilizables de la interfaz.
* `pages/` — Vistas principales de la aplicación.
* `services/` — Servicios para realizar peticiones a APIs.
* `hooks/` — Hooks personalizados.
* `context/` — Contextos globales de React.
* `utils/` — Funciones auxiliares.
* `assets/` — Recursos utilizados por la aplicación.

### Backend

La carpeta `backend` contiene la estructura destinada al servidor:

* `config/` — Configuración del servidor y servicios externos.
* `controllers/` — Lógica de las operaciones solicitadas.
* `routes/` — Definición de las rutas de la API.
* `services/` — Comunicación con servicios externos.
* `models/` — Modelos y estructuras de datos.
* `middleware/` — Middleware para procesar solicitudes.
* `database/` — Recursos relacionados con la base de datos.

## Acuerdos de trabajo

* Trabajar utilizando ramas de Git para desarrollar nuevas funcionalidades.
* Mantener la rama `main` estable.
* Utilizar la rama `desarrollo` para integrar los avances del proyecto.
* Realizar commits frecuentes y descriptivos.
* Subir los cambios a GitHub de manera incremental.
* Evitar subir archivos sensibles como claves de API o archivos `.env`.
* Mantener una estructura de carpetas organizada y fácil de mantener.
* Revisar los cambios antes de realizar un `merge` a la rama principal.
* Documentar las funcionalidades importantes del proyecto.

## Control de versiones

El proyecto utiliza Git y GitHub para llevar un control de versiones y registrar los avances de manera incremental.

La rama de desarrollo utilizada actualmente es:

`desarrollo`
