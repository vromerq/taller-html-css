# Taller HTML5 + CSS 
 Realizado por 
 Valery Carolina Romero Quevedo: 20251578052
 Sara Quintero Garcia: 20251578046
Universidad Francisco Jose de Caldas (Programación Multinivel)

## Objetivo 
Desarrollamos un sitio web llamado Alquimia's Restaurant / Roma Amor con el objetivo de comprender la estructura detrás de una página web y aprender a manipular su apariencia mediante HTML5 y CSS. El sitio busca transmitir la atmósfera cálida de una trattoria tradicional, ofreciendo una navegación intuitiva que incluye la historia del restaurante, un menú categorizado y detallado, la ubicación de sus sedes en la ciudad y un formulario interactivo para la reserva de mesas. Además, el proyecto implementa un diseño completamente responsivo que garantiza una visualización óptima tanto en computadoras de escritorio como en dispositivos móviles.   
## Variante asignada 
Contexto: Restaurante (Sitio web gastronómico para una trattoria de cocina italiana tradicional (Alquimia's Restaurant / Roma Amor).)

Restricción visual: Estética clásica refinada utilizando una paleta basada en tonos borgoña/vino, (Paleta clara + 1 color de acento)

Requisito técnico: 
1. 3 tarjetas con Flexbox
En el CSS aplicamos display: flex; flex-wrap: wrap; en .cards y flex: 1 1 280px en .card. Además, en las categorías del menú y en las sedes tienes grupos de 3 y más tarjetas organizadas con Flexbox.

2. CSS variables obligatorias
Al inicio del CSS declaramos el bloque :root con variables como --color-primary, --color-accent, --color-bg, --space, etc., y fues usado en todo el documento.

3. Responsive a 390 px
Contiene la etiqueta <meta name="viewport" content="width=device-width, initial-scale=1.0"> en el HTML y una Media Query @media (max-width: 700px) en el CSS que reorganiza la navegación y las tarjetas en una sola columna, adaptándose perfectamente a teléfonos móviles de 390px.

4. Navegación con 4 anclas
Nuestro <nav> incluye 5 enlaces de ancla (#inicio, #menu, #nosotros, #sedes, #contacto)
## Tecnologías 
HTML5, CSS3, Git y GitHub. 
 
## Cómo ejecutar 

https://vromerq.github.io/taller-html-css/

Clonar el repositorio o descargar la carpeta del proyecto.

Abrir el archivo index.html directamente en cualquier navegador web moderno (Chrome, Firefox, Edge, Safari).
 
## Decisiones de diseño 

Elección de paleta de colores y estética visual (Trabajo propio):
Elegimos manualmente la paleta cromática sin intervención de IA para transmitir la atmósfera cálida y tradicional de una trattoria romana. Seleccionamos el rojo vino (#8b0000) como color principal para reflejar elegancia e identidad gastronómica, combinado con un fondo crema suave (#f4ebd9) para una lectura descansada y acentos dorados (#d4af37) que resaltan detalles clave y botones.

Estructura, contenido del menú y maquetación visual:
Definimos por nuestra cuenta la ubicación de cada sección dentro de la página, así como la creación y redacción completa de los platos, ingredientes, precios y categorías del menú (Antipasto, Primo Piatto, Secondo Piatto, Contorno, Dolce y Bevande). Organizamos el contenido para mantener una jerarquía clara entre la historia, las sedes y la reserva.

Implementación de Flexbox para tarjetas y adaptabilidad:
Decidimos utilizar Flexbox (display: flex, flex-wrap: wrap) para organizar las tarjetas de los platos y las sedes. Esta elección técnica nos permitió lograr una cuadrícula dinámica que distribuye el espacio de forma limpia en pantallas grandes y se reorganiza de manera fluida en formato vertical al visualizarse en dispositivos móviles
 
## Uso de IA 
La Inteligencia Artificial fue utilizada como un asistente técnico y orientador instructivo a lo largo de todo el desarrollo del taller, permitiéndonos mantener el control creativo y técnico del proyecto mientras resolvíamos dudas de maquetación y diseño.

El apoyo recibido por la IA se enfocó en los siguientes puntos:

Orientación en diseño y contenido: Nos presentó distintas opciones de menús italianos y combinaciones de paletas de color, lo que nos facilitó explorar ideas para seleccionar los platos finales y encontrar el tono exacto de color que buscábamos para nuestra trattoria.

Organización y estructuración del trabajo: Nos ayudó a estructurar la lógica del desarrollo, guiándonos paso a paso sobre cómo alcanzar el resultado deseado y explicándonos los conceptos detrás del código sin realizar el trabajo por nosotras.

Resolución de dudas y problemas: Funcionó como un soporte técnico en tiempo real para resolver inquietudes específicas y depurar errores que surgieron durante la escritura del HTML y CSS.

Verificación de buenas prácticas: Validó la correcta estructura semántica en HTML5 (uso de etiquetas como section,article,header,footer) y confirmó el cumplimiento de las reglas de responsividad en CSS (@media queries, Flexbox) para garantizar que la página funcionara en distintos tamaños de pantalla.

Registro de evidencias: evidencias/ia/registro_ia.md
 
## Evidencias 
- Preguntas manuscritas: Estas estan adjuntas a una carpeta que incluye 4 fotos de las respuestas en una carpeta llamada Evidencias
