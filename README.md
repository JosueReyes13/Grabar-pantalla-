# Proyecto de Capturadora de Video
Este proyecto es una aplicación web que te permite la captura y grabación de video utilizando la API getDisplayMedia de WebRTC. 
La aplicación está compuesta por tres archivos principales: grabar.js, index.html y styles.css.

## Archivos
### grabar.js
Este archivo contiene la lógica principal para capturar y grabar video desde la pantalla. Incluye:

- Configuración inicial: Selección de elementos DOM y verificación del navegador.
- Función handleSuccess: Configuración del MediaRecorder para grabar el flujo de video y gestionar la descarga del archivo grabado.
- Función handleError: Manejo de errores al intentar acceder a la pantalla para grabar.
- Función errorMsg: Muestra mensajes de error en el DOM.
- Evento click del botón startButton: Inicia la captura de la pantalla y comienza la grabación.

## index.html
Este archivo contiene la estructura HTML de la aplicación. Incluye:

- Contenedor principal: Un div con el ID container.
- Elemento video: Muestra el flujo de video de la pantalla capturada.
- Botones: Para iniciar la grabación y seleccionar opciones avanzadas.
- Sección de opciones avanzadas: Permite seleccionar el tipo de superficie a capturar.
- Mensajes de error: Un contenedor para mostrar mensajes de error.

## Instrucciones
1. Clonar el repositorio: Clona este repositorio en tu máquina local.
2. Abrir index.html: Abre el archivo index.html en tu navegador.
3. Iniciar la grabación: Haz clic en el botón "⭕ Iniciar Grabación" para comenzar a grabar tu pantalla.
4. Opciones avanzadas: Si estás usando Chrome versión 107 o superior, puedes seleccionar las opciones avanzadas para elegir el tipo de superficie a capturar.

## Dependencias
Este proyecto utiliza la biblioteca adapter.js de WebRTC para la compatibilidad del navegador.
