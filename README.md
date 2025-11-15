# Ejercicios Módulo 3 - Sprint 2 - Trabajo Práctico 3

Este repositorio contiene la estructura de un proyecto desarrollado con Node.js, Express y MongoDB:

- carpeta llamada `controllers`: contiene los controladores que manejan las solicitudes HTTP y utilizan la capa de servicios para obtener datos.
- carpeta llamada `models`: define las estructuras de datos utilizadas en el proyecto.
- carpeta llamada `repositories`: implementa la capa de persistencia.
- carpeta llamada `services`: contiene la lógica de negocio para las distintas operaciones.
- carpeta llamada `views`: define los datos en el formato adecuado.
- carpeta llamada `routes`: define las rutas de la API y las asocia con los controladores correspondientes.
- archivo `app.mjs`: configura el servidor Express, conecta a MongoDB y maneja las solicitudes a las diversas rutas.
- archivos `package.json` y `package-lock.json`: contienen la configuración de dependencias del proyecto.

## Notas adicionales
- La carpeta `node_modules/` fue excluida del repositorio mediante `.gitignore`.