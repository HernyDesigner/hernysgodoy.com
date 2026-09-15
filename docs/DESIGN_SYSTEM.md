# Design System

## Direccion visual

Marca personal con estetica oscura, tecnologica, minimalista y de alto contraste. El sistema actual usa fondo negro, tipografia sans, acentos violetas, tarjetas oscuras, bordes sutiles y animaciones.

## Colores principales

- Negro base: `#000000`.
- Negro alternativo: `#050505`.
- Violeta principal: `#871DEE`.
- Violeta Tailwind recurrente: `purple-600`.
- Blanco: `#ffffff`.
- Gris claro de texto: valores Tailwind como `text-white/60`, `text-zinc-400`, `text-gray-400`.

## Tipografia

`css/style.css` importa Montserrat:

```css
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');
```

Uso general:

- Titulos grandes uppercase.
- Texto secundario con opacidad reducida.
- Microcopy con estilo mono o tracking amplio cuando se busca tono tecnico.

## Layout

Patrones actuales:

- Secciones full viewport o casi full viewport.
- Padding lateral responsive con `px-8 md:px-16`.
- Grids responsive para servicios.
- Layout mobile-first apoyado en clases Tailwind `md:` y `lg:`.
- Overlay mobile full-screen.

## Componentes visuales

### Loader 3D

Loader inicial con cubo rotativo basado en SVG. Comunica identidad visual, pero debe tener fallback para evitar bloqueo de acceso si falla JavaScript.

### Fondo `a-waves`

Custom element con SVG animado y ruido. Debe respetar rendimiento y movimiento reducido.

### Cards de servicios

Tarjetas oscuras con borde, icono SVG inline, titulo, texto y microcopy.

### CTA principal

Boton animado hacia WhatsApp. Mantenerlo claro, visible y con destino aprobado.

### Navbar y menu mobile

Navbar fijo que aparece tras el loader. Menu mobile full-screen con links internos.

## Movimiento

El proyecto usa movimiento como parte central de la identidad. Toda mejora debe contemplar:

- Estado reducido para `prefers-reduced-motion`.
- No bloquear contenido esencial detras de animaciones.
- Evitar scroll hijacking agresivo.
- Mantener navegacion por teclado.

## Assets

- Logos SVG en `img/`.
- Foto personal `img/hernysgodoy-foto.jpg`.
- Video `media/H-3D.mp4`.
- Favicon PNG e ICO.

No reemplazar assets de marca sin aprobacion.

