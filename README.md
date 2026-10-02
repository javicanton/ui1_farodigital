# El Faro de Puerto Vera (prototipo)

Medio ficticio del Proyecto de Innovación Docente **NewsroomLab IA** (Grado en Periodismo, Universidad Isabel I, curso 2026-2027). Sitio estático en HTML y CSS, sin dependencias, listo para GitHub Pages.

## Estructura

| Archivo | Contenido |
|---|---|
| `index.html` | Portada del diario (una pieza de ejemplo por módulo M1 a M5) |
| `noticia.html` | Plantilla de noticia con aviso de simulación y ficha del encargo |
| `sobre.html` | Qué es el medio, encargos por módulo, normas de publicación y retirada |
| `puerto-vera.html` | Ficha enciclopédica de la ciudad ficticia (contexto y personajes) |
| `assets/css/style.css` | Estilos del diario |
| `assets/css/wiki.css` | Estilos de la enciclopedia |
| `robots.txt` y `.nojekyll` | Bloqueo de indexación y publicación tal cual |

## Publicar en GitHub Pages

1. Crea un repositorio (por ejemplo, `faro-puerto-vera`) y sube el contenido de esta carpeta a la raíz.
2. En el repositorio: **Settings > Pages > Build and deployment > Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos estará en `https://<usuario>.github.io/faro-puerto-vera/`.

## Publicar una pieza nueva

1. Duplica `noticia.html` con un nombre descriptivo (por ejemplo, `2026-11-verificacion-tasa-basuras.html`).
2. Cambia título, entradilla, firma, cuerpo y la **ficha del encargo**. No quites la banda de simulación ni el recuadro de aviso.
3. Enlázala desde `index.html`.

## Salvaguardas incluidas

- Banda «SIMULACIÓN» en todas las páginas y aviso en el pie.
- Etiqueta de módulo en cada pieza y aviso dentro del cuerpo de cada noticia.
- `noindex` en todas las páginas y `robots.txt` que bloquea buscadores.
- Imágenes ilustrativas rotuladas como simulación; datos marcados como sintéticos.

## Cambiar el nombre del medio

Busca y reemplaza «El Faro de Puerto Vera» en los cuatro HTML.
