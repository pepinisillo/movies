# Movies (HTML + CSS)

Demo publicada en GitHub Pages: [pepinisillo.github.io/movies/](https://pepinisillo.github.io/movies/)

## Descripción
Proyecto para practicar **HTML y CSS** creando:
- una página de **detalle de una película** (`index.html`)
- una página de **detalle de un actor** (`actor-yuuichirou.html`)

Ambas páginas comparten un estilo visual oscuro y moderno y utilizan **flexbox** y **media queries** para ser responsivas.

## Páginas
- `index.html` -> Detalle de la película
- `actor-yuuichirou.html` -> Detalle del actor

## Archivos CSS
- `css/style.css` -> estilo de la página de la película
- `css/actor.css` -> estilo de la página del actor

## Flexbox y responsive (media queries)
El layout se construye principalmente con `display: flex` (por ejemplo, para el hero, el listado/columns de contenido y las cards del cast/relacionados).

El diseño se ajusta a escritorio y móvil usando `@media (max-width: 900px)`:
- cambia la dirección/ubicación del layout (pasa a columna en pantallas pequeñas)
- ajusta tamaños de elementos para que no se rompa en el celular