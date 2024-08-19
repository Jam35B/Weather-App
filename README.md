# Weather App

Este proyecto es una aplicación web construida con React que se comunica con la API de [OpenWeather](https://openweathermap.org/) para mostrar datos del clima de una ciudad específica. 

## Características

- **Búsqueda por ciudad**: Los usuarios pueden ingresar el nombre de una ciudad para obtener el clima actual.
- **Datos del clima**: Muestra la temperatura, la humedad, la velocidad del viento, y un icono representativo del estado del tiempo.
- **Manejo de errores**: Validación de entradas y manejo de errores en la respuesta de la API.
- **Interfaz amigable**: Diseño sencillo y fácil de usar.

## Tecnologías Utilizadas

- **React**: Biblioteca de JavaScript para la construcción de interfaces de usuario.
- **API de OpenWeather**: Proporciona datos actualizados del clima.
- **CSS**: Para el estilo y diseño de la aplicación.

## Instalación

Sigue estos pasos para clonar e instalar este proyecto en tu máquina local.

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/weather-app.git

2. Navega al directorio del proyecto:
   ```bash
   cd weather-app
3. Instala las dependencias necesarias:
   ```bash
    npm install
   
Configuración
Antes de ejecutar la aplicación, necesitarás obtener una clave API de OpenWeather y configurarla en tu entorno de desarrollo.

Crea un archivo .env en la raíz del proyecto:

Agrega la siguiente variable de entorno en el archivo .env:
VITE_APP_ID=tu_clave_api

Uso
Para iniciar la aplicación en modo de desarrollo, ejecuta:

     ```bash
    npm run dev
Esto abrirá la aplicación en http://localhost:3000 en tu navegador.

Estructura del Proyecto
src/
components/Weather.jsx: Componente principal que maneja la lógica de búsqueda y muestra los datos del clima.
assets/: Directorio que contiene los iconos utilizados en la aplicación.
Weather.css: Archivo de estilos para la aplicación.
