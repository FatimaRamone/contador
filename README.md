Contador de Palabras

Este proyecto es una página web simple que implementa un formulario para enviar un mensaje, con una funcionalidad añadida que cuenta los caracteres restantes mientras el usuario escribe en un campo de texto. Utiliza HTML, JavaScript y un servicio externo para enviar el formulario de manera eficiente.
Funcionalidades

    Formulario de contacto:
        Permite al usuario ingresar su dirección de correo electrónico y un mensaje.
        Los datos del formulario se envían a través de Formspree, un servicio para manejar formularios sin necesidad de servidor propio.

    Contador de caracteres:
        Muestra cuántos caracteres quedan por escribir mientras el usuario llena el campo de texto.
        El límite de caracteres está establecido en 100, y se muestra en tiempo real cuántos caracteres quedan disponibles.

    Interactividad:
        Cada vez que el usuario escribe en el campo de texto, el contador se actualiza automáticamente para reflejar los caracteres restantes.

Estructura del Proyecto

    HTML:
        El formulario incluye dos campos: uno para la dirección de correo electrónico y otro para el mensaje.
        Un área de texto (textarea) que tiene un límite de caracteres (100), con un contador dinámico que muestra los caracteres restantes.

    CSS:
        El diseño es muy básico, sin estilos complejos, para centrarse en la funcionalidad del formulario.

    JavaScript:
        Se añade un eventListener al campo de texto para detectar cada cambio en su contenido.
        Calcula el número de caracteres restantes y actualiza el contador de caracteres en la página en tiempo real.

Instrucciones de Uso

    Abrir el archivo HTML en un navegador web.
    Llenar el formulario:
        Introduce tu dirección de correo electrónico en el campo correspondiente.
        Escribe tu mensaje en el área de texto. A medida que escribas, verás el contador de caracteres actualizarse.
    Enviar el formulario:
        Cuando hayas terminado de escribir, haz clic en el botón "Send" para enviar el mensaje a través de Formspree.

Requisitos

    Un navegador web moderno que soporte HTML5 y JavaScript.
    El formulario utiliza el servicio Formspree para enviar los datos del formulario, por lo que no es necesario un backend propio.

