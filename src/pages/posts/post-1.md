---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Componentes'
pubDate: 2026-05-19
description: 'Aqui podemos ver los requisitos necesarios y el proceso de la instalacion de Astro.'
author: 'Paula Alejandra Tabares'
image:
    url: 'https://images.seeklogo.com/logo-png/42/1/astro-logo-png_seeklogo-428045.png'
    alt: 'Logo de Astro'
tags: ["astro", "bloguear", "aprender en público"]
---
# Componentes

Los componentes son una de las características más útiles de Astro. Permiten reutilizar partes de una página sin tener que escribir el mismo código varias veces.

En este proyecto se utilizan varios componentes, como el encabezado (Header), el menú de navegación (Navigation) y el pie de página (Footer). Estos elementos aparecen en todas las páginas del sitio, por lo que resulta más práctico crearlos una sola vez y reutilizarlos.

Por ejemplo, podemos crear un componente llamado Header.astro:

```astro
<header>
  <h1>Manual Técnico Astro</h1>
</header>
```

Después, simplemente lo importamos donde lo necesitemos:

```astro
---
import Header from "../components/Header.astro";
---

<Header />
```

Lo mismo ocurre con otros componentes como Navigation y Footer. De esta manera, si queremos cambiar algo del diseño, solo tendremos que modificar el componente y los cambios se reflejarán en todas las páginas donde se esté utilizando.

El uso de componentes ayuda a mantener el proyecto organizado, facilita el mantenimiento del código y permite desarrollar sitios web de una forma más rápida y eficiente.


