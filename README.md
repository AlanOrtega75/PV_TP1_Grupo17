# Trabajo Práctico N°1 Grupo 17: Gestión de Proyectos Educativos

Este es el Trabajo Practico N°1, La página cuenta con una sección de novedades, galería de proyectos y perfiles de los integrantes, este TP se realizo de manera un poco diferente
no se subieron las versiones anteriores a GitHub, solo la base del TP, pero si intercambiamos msjs por Whatsapp, y diviendonos ciertos puntos cada uno, aun tenemos ciertos inconvenientes
y confusiones a la hora de usar GitHub, esperamos solucionarlos en los proximos TPs, Alan se especializo en CSS y Emanuel en HTML, eramos un grupo de 5 estudiantes, pero el resto directamente no se comunico con nosotros, dejandonos algo cortos de tiempo.
Recalco que Alan sera el unico con movimientos en GitHub de momento, en las proximas entregas se espera que Emanuel pueda solucionar sus problemas tecnicos 

Saludos Cordiales

## Integrantes

* **Alan M. Ortega** - [Usuario de GitHub](https://github.com/AlanOrtega75)
* **Emanuel J. Valeriano** - [Usuario de GitHub](https://github.com/Emanuel-J-Valeriano)

## Construcción de las Páginas HTML

El sitio fue desarrollado siguiendo una estructura modular y organizada, enfocada en la claridad y la navegación fluida:

* **Estructura Multi-página:** El proyecto se divide en tres archivos principales (`index.html`, `proyectos.html` y `perfil.html`), lo que permite separar las noticias, la galería de trabajos y la información del equipo de forma ordenada.
* **Uso de HTML5 Semántico:** Implementamos etiquetas como `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`. Esto ayuda a que el código sea más fácil de leer y que el navegador entienda mejor la jerarquía de la información.
* **Sistema de Tarjetas (Cards):** Para las secciones de "Proyectos" y "Perfiles", utilizamos una estructura de contenedores repetibles. Esto facilita que todos los elementos se vean iguales y sean fáciles de actualizar.
* **Vinculación de Recursos:** Todas las páginas están correctamente enlazadas mediante un menú de navegación y apuntan de manera organizada a la carpeta de imágenes (`img/`) y a la hoja de estilos externa (CSS).
* **Atributos de Accesibilidad:** Se incluyeron etiquetas `alt` en todas las imágenes de los proyectos y perfiles para asegurar que el contenido sea comprensible para todos los usuarios.

## Tecnologías y Técnicas de CSS Utilizadas
    
Para el diseño visual de este sitio, nos enfocamos en crear una interfaz moderna y organizada utilizando las siguientes herramientas de CSS:

* **Variables CSS (`:root`):** Centralizamos la paleta de colores (como el azul institucional y los tonos de hover) para que el diseño sea consistente y fácil de actualizar.
* **CSS Grid:** Lo utilizamos para la estructura principal de la galería de proyectos y las estadísticas, permitiendo una cuadrícula de 3 columnas que se adapta al espacio.
* **Flexbox:** Fundamental para la alineación del menú de navegación y para organizar los elementos dentro de las tarjetas.
* **Selectores Avanzados:** Uso de pseudo-clases como `:hover` para interactividad en botones.
* **Optimización de Imágenes:** Aplicamos `object-fit: cover` en todas las fotos de perfil y de proyectos para asegurar que mantengan su proporción sin deformarse, logrando un aspecto uniforme en todo el sitio.
* **Diseño de Componentes:** Estilización personalizada de enlaces y botones para mejorar la experiencia del usuario.