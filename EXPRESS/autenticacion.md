# Ejercicio: Creación de un Sistema de Autenticación

## Objetivo

Construir una API que permite a los usuarios registrarse, iniciar sesión y acceder a una ruta protegida mediante tokens de autenticación.

## Requisitos previos

- Tener instalado [Node.js](https://nodejs.org/) en tu sistema.
- Conocimientos básicos de JavaScript, Node.js y conceptos de autenticación.
- Instalar [Postman](https://www.postman.com/) o usar `curl` para probar la API.

## Criterios de aceptacion

1. Crear un endpoint para registrar un usuario con una contraseña encriptada
2. Crear un endpoint para iniciar sesion dado un usuario y contraseña
3. Crear un endpoint protegido que diga hola mundo! si el usuario está autorizado o que saque un error 401 si no está autorizado.