
# Hamburger Menu

Un simple menú hamburguesa con animaciones interactivas.

## Contenido

- [Demo](#demo)
- [Características](#características)
- [Instalación](#instalación)
- [Uso](#uso)
- [Personalización](#personalización)
- [Licencia](#licencia)

## Demo

[https://codepen.io/Kirgo/pen/KKERxEd](https://codepen.io/Kirgo/pen/KKERxEd)

![IMG](02_CSS_CHALLENGE/CAPTURA_MENU_HAMBURGERSA.png) <!-- Sustituye con un enlace o imagen de tu demo si tienes uno -->

## Características

- Menú hamburguesa interactivo con animaciones suaves.
- Escrito en HTML, SCSS y jQuery.
- Fácil de integrar en proyectos web.

## Instalación

1. Clona este repositorio o descarga los archivos directamente.

   ```bash
   git clone https://github.com/tu-usuario/tu-proyecto.git
   ```

2. Abre el archivo `index.html` en tu navegador.

## Uso

1. Agrega el siguiente código HTML a tu proyecto donde desees mostrar el menú hamburguesa:

   ```html
   <!-- Asegúrate de incluir jQuery antes de este código -->
   <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>

   <link rel="stylesheet" href="style.css">
   <script src="script.js"></script>

   <div class="frame">
       <div class="center">
           <div class="menu-icon">
               <div class="line-1 no-animation"></div>
               <div class="line-2 no-animation"></div>
               <div class="line-3 no-animation"></div>
           </div>
       </div>
   </div>
   ```

2. Personaliza el aspecto según tus necesidades.

## Personalización

Puedes personalizar el menú hamburguesa ajustando los colores, tamaños y animaciones en el archivo `style.scss`. Las variables están definidas al principio del archivo para facilitar la modificación.

## Licencia

Este proyecto está bajo la [Licencia MIT](LICENSE).

¡Siéntete libre de personalizar este README según tus necesidades! Asegúrate de incluir información adicional que pueda ser relevante para quienes utilicen o contribuyan a tu proyecto.
