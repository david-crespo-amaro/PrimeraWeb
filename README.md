# Proyecto Web Individual - Primera Web

Aquí está el código fuente de mi página web para la asignatura de Fundamentos de Ingeniería Informática. El objetivo ha sido crear una web ordenada, limpia y que cumpla con los requisitos.

## Autor
**David Crespo Amaro**

## Descripción del Proyecto

Este proyecto consiste en la implementación de una web desarrollada bajo los estándares de HTML5 y CSS. Más allá de la maquetación visual, el desarrollo se ha abordado como un proyecto de software, priorizando una arquitectura de archivos limpia.

El sitio web se estructura separando estrictamente el contenido (HTML en carpeta public) de la presentación (hojas de estilo en css), implementando una metodología de estilos en cascada que combina reglas globales con archivos específicos para cada sección. El resultado es una aplicación web estática, robusta y responsive, que cumple rigurosamente con los requisitos de versionado y organización exigidos en la asignatura de Fundamentos de la Ingeniería Informática.

### Tecnologías utilizadas 
- **HTML5:** Para una estructura correcta y semántica.
- **CSS3:** He implementado una arquitectura de estilos. Utilizando un archivo `styles.css` para los estilos globales (comunes a toda la web) y **archivos CSS específicos para cada página HTML** (por ejemplo, `about.css`, `topic.css`), lo que facilita el mantenimiento y la especificidad del diseño.
- **Git & GitHub:** Para el control de versiones y subir la web.

### Estructura de Páginas 

He organizado la web en estas secciones:

* **Inicio (`index.html`):** Portada principal de la web.
* **Sobre Mí (`public/about.html`):** Mi perfil profesional, biografía, CV y redes sociales.
* **Contacto (`public/contact.html`):** Un formulario para poder contactar conmigo.
* **Grado (`public/degree.html`):** Información sobre el Grado en Ingeniería Informática y sus asignaturas.
* **Fundamentos (`public/fii.html`):** Detalle específico de la asignatura "Fundamentos de la Ingeniería Informática".
* **Red (`public/net.html`):** Enlaces a las webs de mis compañeros de clase.
* **Tema (`public/topic.html`):** Un artículo sobre **Hacking Ético**.

## Dificultades durante el desarrollo

Al tener base técnica previa, la parte de escribir código HTML y CSS no me ha dado problemas. Sin embargo, sí he tenido que prestar atención a otros detalles:

1.  **El flujo de trabajo con Git:** Estoy acostumbrado a trabajar de otra forma, así que tuve que adaptarme para hacer *commits* separados por cada página nueva tal y como pedía el enunciado, en lugar de subirlo todo de golpe.
2.  **Organización de carpetas:** Al meter los HTML en la carpeta `public/` y dejar el `index.html` fuera, tuve que revisar bien todas las rutas (`../`) para que no se rompieran los enlaces a los estilos y las imágenes.

## Conclusiones

Esta práctica me ha venido bien para refrescar conceptos de maquetación pura que a veces se olvidan cuando usas frameworks más complejos. También me ha servido para ser más disciplinado con el orden de los archivos y con el uso de Git para documentar los pasos del proyecto.

## Cómo ver el sitio

La web está publicada en GitHub Pages y se puede ver aquí:
[**Visitar Sitio Web**](https://david-crespo-amaro.github.io/PrimeraWeb/)