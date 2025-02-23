Interacción con IA

Este proyecto es una interfaz web que permite interactuar con un modelo de inteligencia artificial mediante una API en un servidor local. Se utiliza HTML, Bootstrap y jQuery para la parte visual e interactiva.

Características

Enviar preguntas a una IA mediante una solicitud POST.

Mostrar respuestas en la interfaz de usuario.

Indicador de carga mientras se obtiene la respuesta.

Uso de Bootstrap 5 para un diseño responsivo.

Requisitos

Servidor en http://localhost:8008/answerQuestion que procese las solicitudes POST.

Un entorno compatible con Bootstrap y jQuery.


/
├── assets/
│   ├── css/
│   │   └── bootstrap.min.css
│   ├── js/
│   │   ├── bootstrap.bundle.min.js
│   │   └── jquery-3.7.1.min.js
├── index.html
├── README.md

Uso

Abrir index.html en el navegador.

Ingresar una pregunta en el campo de texto.

Presionar el botón "Preguntar" para enviar la solicitud.

Ver la respuesta generada por la IA en pantalla.

Tecnologías Utilizadas

HTML5: Estructura del proyecto.

Bootstrap 5: Estilizado y diseño responsivo.

jQuery: Manejo de eventos y peticiones AJAX.

Fetch API: Enviar solicitudes POST al backend.

API del Backend