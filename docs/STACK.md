# STACK.md

## Stack actual

El sitio funciona actualmente sin sistema de build.

### Frontend

- HTML5
- CSS3
- JavaScript vanilla

### CSS

- Tailwind CSS vía CDN
- CSS propio en `css/style.css`
- estilos inline o embebidos en algunos prototipos

### JavaScript / animación

- JavaScript vanilla
- GSAP 3.13.0 vía CDN
- Lenis 1.3.11 vía CDN
- custom element `<a-waves>`
- IntersectionObserver
- script externo relacionado con `Noise`

### Assets

- SVG
- imágenes raster
- video MP4

### Build

Actualmente no existe:

- npm
- package.json
- Vite
- webpack
- PostCSS
- Tailwind local

No introducir estas herramientas automáticamente.

Cualquier migración del stack deberá plantearse primero como una decisión arquitectónica.

---

## Archivo principal

`index.html`

## CSS principal

`css/style.css`

## JavaScript

Actualmente existe JavaScript inline dentro de `index.html`.

También existen:

- `js/script-04.js`
- `js/script-05.js`

que no parecen formar parte de la versión activa actual.

No asumir que deben utilizarse.
