# ESCUELA SUPERIOR POLITÉCNICA DEL LITORAL
## FACULTAD DE INGENIERÍA EN ELECTRICIDAD Y COMPUTACIÓN

**Proyecto 02 - Fase 3: Desarrollo - Sprint 1**  
**Materia:** Desarrollo de Aplicaciones Web y Móviles  
**Evento:** Chancho Fest 2026 - Parque Samanes  
**Integrantes:** María Cristina Andrade Echeverría & Robert Jaren Pilco Almeida  

---

## Contenido

- [Análisis](#análisis) .................................................................................................... 2
- [Planificación](#planificación) .......................................................................................... 2
- [Diseño](#diseño) ........................................................................................................ 2
- [Implementación](#implementación) ........................................................................................ 2
- [Despliegue](#despliegue) ................................................................................................ 3
- [Bibliografía](#bibliografía) ............................................................................................ 3

---

## Análisis

Se evaluaron tres plantillas gratuitas de HTML5 UP.

Directive tiene una estructura de una sola página con desplazamiento vertical. Su diseño es minimalista, directo y totalmente responsivo, y su código limpio facilita la personalización, lo que resulta ideal para presentar nuestros datos de forma rápida.

Ethereal se basa en un desplazamiento horizontal. Su diseño es muy llamativo y visual, pero se adapta peor a este proyecto, ya que el scroll horizontal dificulta la lectura continua y natural de un reporte de resultados.

Dimension es un diseño interactivo que abre el contenido en ventanas emergentes sobre una imagen de fondo fija. Su navegación es atractiva, pero fragmenta demasiado los datos recopilados y entorpece una lectura ágil.

### Tabla comparativa de plantillas (HTML5 UP)

| Criterio | Directive (Seleccionada) | Ethereal | Dimension |
| :--- | :--- | :--- | :--- |
| **Estructura** | Una sola página (*single-page*) con bloques modulares verticales. | Múltiples paneles con desplazamiento horizontal continuo. | Basada en ventanas modales/popups sobre fondo estático. |
| **Navegación** | *Scroll* vertical natural e intuitivo para cualquier dispositivo. | *Scroll* horizontal (menos fluido para reportes de datos). | Menú interactivo con apertura de cuadros superpuestos. |
| **Diseño** | Minimalista, directo, limpio y enfocado en la lectura. | Muy visual, dinámico y con fuerte contraste. | Estilo tarjeta centralizada, compacto y envolvente. |
| **Adaptabilidad** | Totalmente responsivo; se reorganiza fluidamente en móviles. | Fluido, pero propenso a desbordes en pantallas reducidas. | Responsivo, aunque el área de lectura es limitada. |
| **Facilidad de personalización** | Muy alta: código HTML5/CSS modular y directo para cambiar assets. | Media: requiere ajustar anchos de paneles y scrolls. | Media-alta: depende de la lógica de scripts para modales. |

---

## Planificación

Decidimos hacer una página sencilla, de una sola hoja, con encabezado, introducción y tres secciones principales, llamadas Comercio y Gastronomía, El Ritmo del Público y La Voz de la Comunidad. También incluimos un botón para conocer más del proyecto y un formulario de contacto.

Primero analizamos los datos de la encuesta, luego organizamos el contenido, elegimos la plantilla y creamos el repositorio con su README. Cada integrante trabajó en su propia rama y los avances se unieron a la rama principal mediante pull requests con revisiones cruzadas. Además, mantuvimos comunicación constante para evitar errores e imprevistos.

### Organización del contenido del sitio

| Nombre de la Sección | Propósito | Datos que se presentarán |
| :--- | :--- | :--- |
| **Header (Inicio)** | Atraer al usuario presentando el tema del proyecto y el evento analizado. | Título "Chancho Fest 2026", subtítulo indicando que es un análisis de datos, ubicación (Parque Samanes) y fechas (2 al 4 de octubre). |
| **Main (Contexto)** | Explicar el propósito del levantamiento de información y la importancia del evento. | Párrafo introductorio sobre el impacto del festival en el comercio local, la integración cultural y el objetivo de recopilar datos reales. |
| **Comercio y Gastronomía** | Informar sobre la oferta gastronómica y el impacto comercial del festival. | Más de 50 preparaciones de cerdo, participación de emprendedores locales y precios accesibles. |
| **El Ritmo del Público** | Reflejar la afluencia ciudadana, horarios pico y actividades artísticas. | Estimación de 30,000 asistentes, shows de música en vivo, concursos y ambiente familiar. |
| **La Voz de la Comunidad** | Presentar los hallazgos y percepciones de la encuesta ciudadana realizada. | Preferencias de consumo, nivel de satisfacción de los asistentes y sugerencias de mejora. |
| **Footer (Contacto)** | Brindar un canal de comunicación para interesados en los resultados del proyecto. | Formulario de contacto y créditos a los desarrolladores. |

---

## Diseño

El diseño visual y de experiencia de usuario, conocido como UI/UX, se definió de forma conjunta, priorizando la coherencia estética y la usabilidad. Tras el análisis comparativo, elegimos Directive porque su enfoque minimalista y directo se alinea con la necesidad de presentar los resultados del Chancho Fest de manera clara y sin distracciones. Su simplicidad también facilitó la integración de los datos recopilados y nos permitió cumplir con la entrega de una primera versión funcional dentro del Sprint 1.

---

## Implementación

Partimos de la plantilla Directive, que descargamos y subimos al repositorio para trabajar sobre ella. Cambiamos los textos de index.html para mostrar la información del evento Chancho Fest y reemplazamos las imágenes pic01, pic02 y pic03 por fotos del evento, eliminando las originales. También modificamos los estilos de assets/css/main.css para que las fotos se vieran completas dentro de su recuadro. En el README.md dejamos escrita la justificación de la plantilla y los créditos de las imágenes, y mantuvimos en el pie de página el crédito a HTML5 UP que exige su licencia.

---

## Despliegue

Todo el código está en un repositorio público de GitHub. Cada integrante trabajó en su propia rama, que se llamaron maria y robert. Cuando los cambios estuvieron listos, los subimos a la rama principal mediante un pull request, revisando antes lo que se modificaba. Después hicimos un git pull en main para confirmar que las imágenes nuevas y los archivos modificados estuvieran allí.

---

## Bibliografía

* El Universo. (2026). *Chancho Fest 2026 reunirá 50 preparaciones de cerdo y shows artísticos en Parque Samanes*. https://www.eluniverso.com/guayaquil/comunidad/chancho-fest-2026-reunira-50-preparaciones-de-cerdo-y-shows-artisticos-en-parque-samanes-la-entrada-es-gratuita-y-se-preve-recibir-a-30000-personas-nota/
* GitHub. (s. f.-a). *About pull requests*. https://docs.github.com/pull-requests
* GitHub. (s. f.-b). *GitHub Pages documentation*. https://docs.github.com/pages
* HTML5 UP. (s. f.-a). *The Creative Commons Attribution 3.0 License*. https://html5up.net/license
* HTML5 UP. (s. f.-b). *Directive*. https://html5up.net/directive
* HTML5 UP. (s. f.-c). *HTML5 UP: Responsive HTML5 and CSS3 site templates*. https://html5up.net/
* Revista Zona Libre. (2026). *El Chancho Fest 2026 presenta 50 ricuras de cerdo, conciertos y show bailable*. https://www.revistazonalibre.ec/2026/09/14/el-chancho-fest-2026-presenta-50-ricuras-de-cerdo-conciertos-y-show-bailable/

---

## Créditos de las imágenes

| Imagen | Dónde se usa | Autor | Fuente |
|---|---|---|---|
| `pic01.jpeg` | Sección «Comercio y Gastronomía» | Revista Zona Libre | [Revista Zona Libre](https://www.revistazonalibre.ec/2026/09/14/el-chancho-fest-2026-presenta-50-ricuras-de-cerdo-conciertos-y-show-bailable/) |
| `pic02.jpeg` | Sección «El Ritmo del Público» | El Universo | [El Universo](https://www.eluniverso.com/guayaquil/comunidad/chancho-fest-2026-reunira-50-preparaciones-de-cerdo-y-shows-artisticos-en-parque-samanes-la-entrada-es-gratuita-y-se-preve-recibir-a-30000-personas-nota/) |
| `pic03.jpeg` | Sección «La Voz de la Comunidad» | Equipo de trabajo (Andrade María y Pilco Robert) | Elaboración propia |

*Las fotografías propias fueron tomadas por los integrantes del equipo durante el Chancho Fest, del 2 al 4 de octubre de 2026, en el Parque Samanes.*

---

*(Créditos originales de la plantilla a continuación)*

Directive by HTML5 UP  
html5up.net | @ajlkn  
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

A simple single pager built around an angular motif (powered by SVG awesomeness). Should work great for a landing page. Also includes default styling for a bunch of standard page elements (uncomment the huge block of commented-out HTML to see it).

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images you can use for pretty much whatever.

(* = Not included)

Feedback, bug reports, and comments are not only welcome, but strongly encouraged :)

AJ  
aj@lkn.io | @ajlkn  

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).

Credits:
* **Demo Images:** Unsplash (unsplash.com)
* **Icons:** Font Awesome (fontawesome.io)
* **Other:** jQuery (jquery.com), Responsive Tools (github.com/ajlkn/responsive-tools)