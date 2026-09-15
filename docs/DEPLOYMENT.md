# Deployment

## Tipo de despliegue esperado

El proyecto puede publicarse como sitio estatico. No requiere servidor de aplicaciones, base de datos ni build obligatorio.

Opciones compatibles:

- GitHub Pages.
- Netlify.
- Vercel como sitio estatico.
- Hosting tradicional con archivos HTML/CSS/JS.

## Entrada de publicacion

La raiz publica debe servir:

```text
index.html
```

Y conservar estas carpetas:

```text
css/
img/
media/
```

## Checklist antes de publicar

- Confirmar que `index.html` es la version correcta.
- Validar numero de WhatsApp oficial.
- Validar email oficial.
- Validar links sociales.
- Agregar o revisar `meta description`.
- Agregar `h1`.
- Definir canonical si existe dominio final.
- Crear `robots.txt` y `sitemap.xml` si el sitio va a indexarse.
- Revisar mobile y desktop.
- Revisar que las dependencias CDN carguen.
- Revisar que `media/H-3D.mp4` pese y cargue aceptablemente.

## Riesgos de despliegue

- Si el CDN de Tailwind falla, la UI puede perder estilos principales.
- Si el script de CodePen falla, el fondo `a-waves` puede romper.
- Si GSAP falla, loader/menu/animaciones pueden no comportarse como se espera.
- Si Lenis falla, la navegacion suave puede degradar.

## Recomendacion para produccion estable

Antes de una publicacion formal:

1. Localizar dependencias criticas.
2. Compilar Tailwind localmente.
3. Definir fallback para loader y animaciones.
4. Optimizar video e imagenes.
5. Agregar SEO tecnico basico.
6. Agregar politica de privacidad si se incorpora medicion o formularios.

