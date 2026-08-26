# Módulo 1 — Web Fundamentals, Git Workflow & Clean Architecture Base

## Proyecto real

Dev Hub & Resource Directory — plataforma colaborativa de recursos para developers.

## Objetivo de esta primera tarea

Maquetación semántica del esqueleto HTML5 de la página principal. Sin CSS todavía — el archivo `src/index.html` lo crean ustedes desde cero.

## Historias de Usuario

**US-1.1** — Como visitante del Dev Hub, quiero ver una cabecera con el nombre de la plataforma y la navegación principal, para identificar el sitio y moverme entre sus secciones.

**US-1.2** — Como visitante, quiero ver una sección principal (hero) que explique qué es el Dev Hub & Resource Directory, para entender el propósito del sitio en los primeros segundos.

**US-1.3** — Como visitante, quiero ver un listado de categorías o recursos destacados estructurado semánticamente, para poder escanear rápido qué contenido hay disponible.

**US-1.4** — Como visitante, quiero ver un pie de página con enlaces secundarios/contacto, para encontrar información adicional sin que estorbe el contenido principal.

## Criterios de Aceptación

- [ ] Un único `<header>`, `<main>` y `<footer>` como landmarks de nivel superior.
- [ ] Un único `<h1>` en toda la página.
- [ ] `<nav>` con lista real (`<ul>`/`<li>`) de enlaces.
- [ ] Al menos dos `<section>` dentro de `<main>`, cada una con su propio `h2`.
- [ ] `<aside>` (si se usa) contiene solo contenido complementario.
- [ ] Imágenes con `alt` descriptivo.
- [ ] HTML válido según el validador de W3C.
- [ ] Clases CSS en convención BEM (`bloque__elemento--modificador`), aunque el CSS llegue después.
- [ ] Trabajo en rama `feature/mod-01-maquetacion-semantica`, commits en Conventional Commits.
- [ ] PR abierto con la plantilla del repo.

## Para investigar

- MDN — [HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) (sección "Content sectioning")
- "HTML5 semantic elements header nav main article section aside footer"
- "WCAG landmarks accessibility"
- "BEM methodology naming convention"
- W3C Markup Validation Service
