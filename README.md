# ⚡ Electro Online

Sitio de e-commerce de una tienda ficticia de electrónica, desarrollado con HTML y CSS como pre-entrega del curso de Front-End.

## Tech Stack

- **HTML5** semántico (`header`, `nav`, `main`, `section`, `article`, `footer`, `table`, `address`)
- **CSS3** puro (Flexbox, Grid, Media Queries, `background-image` y `linear-gradient`)
- **Google Fonts** — familia única: [Sora](https://fonts.google.com/specimen/Sora)
- **Font Awesome 6** por CDN (íconos de carrito, estrellas y redes sociales)
- **Formspree** para el formulario de contacto

## Estructura

```
pre-entrega/
├── index.html
├── styles.css
├── pages/
│   ├── tienda.html
│   ├── contacto.html
│   └── carrito.html
├── estilos/
│   ├── tienda.css
│   ├── contacto.css
│   └── carrito.css
├── img/
│   ├── logo1.png
│   ├── hero4.jpg
│   ├── productos/
│   ├── banner/
│   ├── people/
│   └── pay/
```

## Features

- Cabecera y lista de navegación compartidas en todas las páginas, con menú que se reorganiza solo con Media Queries (sin menú hamburguesa).
- Hero con `background-image` + `linear-gradient` y enlace "Comprar".
- Productos en Flexbox (4, 3, 2 y 1 por fila según el ancho de pantalla).
- Reseñas en CSS Grid de 3 columnas (2 y 1 en pantallas chicas).
- Banner promocional con imagen de fondo y degradado.
- Video de YouTube embebido y mapa de Google Maps con `loading="lazy"`.
- Newsletter con formulario de correo en todas las páginas.
- Formulario de contacto con Formspree (nombre, correo, asunto y mensaje con `label` y `required`).
- Carrito estático con `<table>`, cupón ilustrativo y bloque de total.
- Accesibilidad: `alt` en imágenes, `title` en iframes, `aria-hidden` en íconos, `scope` en encabezados de tabla y un solo `<h1>` por página.

## Vistas

| Sección | Descripción |
|---|---|
| Home (`index.html`) | Hero, 8 productos, banner, video, reseñas, newsletter y footer |
| Tienda (`pages/tienda.html`) | Cabecera con imagen y catálogo completo de 8 productos |
| Contacto (`pages/contacto.html`) | Formulario con Formspree, equipo, mapa y newsletter |
| Carrito (`pages/carrito.html`) | Tabla estática de productos, cupón y total con enlace a contacto |

## Author

**Nicolas Marsilio** — estudiante del curso de Front-End, comisión **26238**.

Sitio publicado: [https://github.com/NicoMarsilio]
