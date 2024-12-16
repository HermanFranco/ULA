

---------Configuración del Servidor Web Local------------------------

Con XAMPP

Descarga e instala XAMPP desde su sitio web oficial.

Abre el Panel de Control de XAMPP y activa el módulo Apache.

Copia la carpeta del proyecto en el directorio htdocs ubicado en el directorio de instalación de XAMPP (por ejemplo, C:\xampp\htdocs\project-folder).

Con WAMP

Descarga e instala WAMP desde su sitio web oficial.

Inicia WAMP y asegúrate de que el servidor Apache esté en ejecución.

Copia la carpeta del proyecto en el directorio www de WAMP (por ejemplo, C:\wamp64\www\project-folder).

--------------Acceso al Proyecto-------------------

Abre tu navegador web.

En la barra de direcciones, escribe:

Para XAMPP: http://localhost/project-folder/

Para WAMP: http://localhost/project-folder/

Si la configuración es correcta, deberías ver la página de inicio del proyecto.

-----------Dependencias Externas----------------------

Fuentes y Librerías

Este proyecto utiliza:

Google Fonts:

Montserrat es la fuente principal utilizada. Está integrada en el archivo HTML mediante un enlace al CDN:

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

CSS Reset:

Asegúrate de que los estilos globales del navegador sean neutralizados por las reglas en assets/css/styles.css.

----------Personalización-------------

Modificar el Estilo

Abre el archivo assets/css/styles.css en tu editor de código.

Realiza cambios según tus necesidades y guarda los ajustes.

Cambiar el Contenido

Abre los archivos HTML relevantes (index.html, arquitectura.html, lenguaje.html, css3.html).

Edita las secciones de contenido dentro de las etiquetas <main> y guarda los cambios.

----------Resolución de Problemas-----------

No aparece la página en el navegador:

Verifica que el servidor Apache esté en ejecución.

Confirma que los archivos del proyecto están en el directorio correcto del servidor local.

Estilos no cargan:

Asegúrate de que la ruta del archivo CSS sea correcta: assets/css/styles.css.

Limpia la caché del navegador (Ctrl+F5 o Cmd+Shift+R).