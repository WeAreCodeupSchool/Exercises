# Ejercicio: Subir Archivos al Servidor

## Objetivo

Construir una API REST que permite a los usuarios subir archivos al servidor y guardarlos en una carpeta específica.

## Requisitos previos

- Tener instalado [Node.js](https://nodejs.org/) en tu sistema.
- Conocimientos básicos de JavaScript y Node.js.
- Instalar [Postman](https://www.postman.com/) o usar `curl` para probar la API.

## Criterios de aceptación

1. Subir un archivo: El API debera ser capaz de subir archivos.
2. Listar archivos subidos: Deberá devolver una lista de los archivos subidos
3. Acceder a un archivo subido: Deberás poder acceder a uno de los archivos subidos.
4. Límite de tamaño de archivo: El endpoint encargado de subir los archivos deberá establecer un limite de 5MB
5. Validación de tipos de archivo: Solo se ponda subir archivos PDF