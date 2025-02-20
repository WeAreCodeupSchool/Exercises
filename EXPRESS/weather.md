# Ejercicio: Consumir una API Externa con Express.js

## Objetivo

Construir una API REST que actúa como un intermediario entre el cliente y una API externa, permitiendo a los usuarios obtener datos de una fuente externa (por ejemplo, datos del clima) a través de tu servidor.

En este ejercicio, utilizaremos la [API OpenWeatherMap](https://openweathermap.org/api) para obtener información sobre el clima de una ciudad específica.

## Requisitos previos

- Tener instalado [Node.js](https://nodejs.org/) en tu sistema.
- Conocimientos básicos de JavaScript y Node.js.
- Una cuenta en [OpenWeatherMap](https://openweathermap.org/) para obtener una **API Key** gratuita.
- Instalar [Postman](https://www.postman.com/) o usar `curl` para probar la API.

## Criterios de aceptación

1. Crea un endpoint para obtener el clima de una ciudad
2. Organiza el proyecto en capas (controllers, routes, services etc...) no tengas miedo en ser creativo con esto organiza todo como mejor te parezca pero que no este todo en un mismo archivo.