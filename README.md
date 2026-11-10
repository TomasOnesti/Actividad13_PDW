# Actividad-13

Descripción del proyecto

Este proyecto consiste en una aplicación web de monitoreo georreferenciado que permite visualizar diferentes puntos de interés sobre un mapa interactivo.

La aplicación utiliza Leaflet y OpenStreetMap para representar ubicaciones geográficas, permitiendo al usuario seleccionar marcadores y consultar información específica de cada ubicación.

Además, incorpora un sistema de alertas sonoras que se activa al hacer clic sobre los marcadores del mapa.

Objetivo

Desarrollar una aplicación web que permita representar y consultar ubicaciones geográficas de manera interactiva, incorporando información descriptiva y notificaciones sonoras para mejorar la experiencia del usuario.

Tecnologías utilizadas

HTML5: estructura de la aplicación.

CSS3: diseño y estilos visuales.

JavaScript: lógica e interactividad.

Leaflet 1.9.4: biblioteca para la creación de mapas interactivos.

OpenStreetMap: proveedor de mapas y datos cartográficos.

Audio HTML5: reproducción de alertas sonoras.

Funcionalidades

Visualización de un mapa interactivo.

Ubicación inicial centrada en la zona de Vicente López, Buenos Aires.

Representación de puntos de interés mediante marcadores.

Visualización de información descriptiva al seleccionar un marcador.

Reproducción de una alerta sonora al hacer clic sobre cada marcador.

Posibilidad de desplazarse y acercar o alejar el mapa.

Puntos de interés

Actualmente, la aplicación cuenta con los siguientes puntos:

Ubicación

Descripción

EEST N°1 Vicente López

Sede central de operaciones y proyectos de 7mo año.

Punto de Monitoreo Norte

Estación de control auxiliar simulada.

Estructura del proyecto

Proyecto/
│
├── index.html
├── styles.css
├── script.js
│
└── assets/
    └── alerta.mp3

Instalación y ejecución

Descargar o clonar el repositorio.

Mantener los archivos dentro de la misma estructura de carpetas indicada anteriormente.

Verificar que el archivo alerta.mp3 se encuentre dentro de la carpeta assets.

Abrir el archivo index.html en un navegador web.

Interactuar con los marcadores para consultar información y escuchar las alertas sonoras.

Nota: Es necesaria una conexión a Internet para cargar los mapas de OpenStreetMap y la biblioteca Leaflet desde sus respectivos servidores.