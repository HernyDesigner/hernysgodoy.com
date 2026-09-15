# SEO Guidelines

## Estado actual

El proyecto tiene SEO tecnico inicial, pero incompleto.

Existe:

- `lang="es"`.
- `charset`.
- viewport.
- `title`.
- favicon.
- contenido textual en HTML.

Falta:

- `meta name="description"`.
- `canonical`.
- Open Graph.
- Twitter Card.
- JSON-LD.
- `robots.txt`.
- `sitemap.xml`.
- `h1` en `index.html`.
- estrategia de headings consistente.
- atributos de performance en imagenes.

## Reglas para nuevas paginas o cambios SEO

- Cada pagina publicable debe tener un unico `h1`.
- El contenido principal debe estar en HTML, no depender de canvas, SVG animado o JS.
- Usar headings en orden logico.
- Cada imagen informativa debe tener `alt` util.
- Imagenes decorativas deben usar `alt=""`.
- Agregar `loading="lazy"` y `decoding="async"` cuando corresponda.
- Definir title y description especificos.
- Agregar canonical cuando exista URL definitiva.
- Agregar Open Graph para compartir en redes.
- Agregar Schema.org solo si representa contenido visible y real.

## Recomendacion para `index.html`

Prioridad alta:

1. Convertir el heading principal del hero en `h1`.
2. Agregar meta description.
3. Agregar Open Graph basico.
4. Definir canonical cuando este confirmada la URL final.
5. Crear `robots.txt` y `sitemap.xml` cuando haya dominio y rutas definitivas.

## SEO para IA / GEO

El sitio debe explicar con claridad:

- Quien es Herny Godoy.
- Que servicios ofrece.
- Para quien trabaja.
- Que problemas resuelve.
- Como contactarlo.
- Que experiencia o enfoque diferencial tiene.

Evitar slogans aislados sin contexto. Priorizar frases autosuficientes y verificables.

## Metricas sugeridas

Cuando el sitio este publicado:

- Impresiones y clics en Search Console.
- Consultas que activan la marca y servicios.
- CTR organico.
- Conversiones por WhatsApp/email.
- Core Web Vitals.
- Indexacion de URLs.

