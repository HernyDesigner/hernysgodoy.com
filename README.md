# 3-Maquetado

Maqueta estatica del sitio de Herny Godoy. El proyecto esta construido con HTML, CSS y JavaScript vanilla, usando dependencias externas por CDN.

## Entrada principal

El archivo principal del sitio es:

- `index.html`

Los demas HTML son versiones, prototipos o piezas auxiliares. No asumir que forman parte de produccion sin revisar `docs/ARCHITECTURE.md`.

## Estructura

```text
3-Maquetado/
├── AGENTS.md
├── README.md
├── docs/
│   ├── PROJECT_CONTEXT.md
│   ├── ARCHITECTURE.md
│   ├── STACK.md
│   ├── DESIGN_SYSTEM.md
│   ├── SEO_GUIDELINES.md
│   ├── CONTENT_GUIDELINES.md
│   ├── DEVELOPMENT_RULES.md
│   └── DEPLOYMENT.md
├── index.html
├── css/
├── js/
├── img/
├── media/
└── otros prototipos HTML
```

## Stack resumido

- HTML estatico.
- CSS propio.
- Tailwind CSS via CDN.
- JavaScript vanilla.
- GSAP via CDN.
- Lenis via CDN.
- Script externo de CodePen para `Noise`.

No hay `package.json`, build local, framework frontend, backend ni base de datos.

## Como abrir el sitio

Abrir `index.html` directamente en el navegador. Para una prueba mas realista, servir la carpeta con un servidor estatico local.

Ejemplo:

```powershell
python -m http.server 8080
```

Luego abrir:

```text
http://localhost:8080/
```

## Documentacion

- `docs/PROJECT_CONTEXT.md`: contexto del proyecto y objetivo.
- `docs/ARCHITECTURE.md`: estructura tecnica y archivos principales.
- `docs/STACK.md`: tecnologias, librerias y dependencias.
- `docs/DESIGN_SYSTEM.md`: reglas visuales y componentes.
- `docs/SEO_GUIDELINES.md`: estado SEO y criterios de mejora.
- `docs/CONTENT_GUIDELINES.md`: tono, contenido y datos sensibles.
- `docs/DEVELOPMENT_RULES.md`: reglas para implementar cambios.
- `docs/DEPLOYMENT.md`: criterios para publicar.

