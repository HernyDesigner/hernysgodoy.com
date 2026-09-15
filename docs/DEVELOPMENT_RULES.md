# Development Rules

## Antes de editar

1. Leer `AGENTS.md`.
2. Confirmar si el cambio aplica a `index.html` o a un prototipo.
3. Revisar `git status --short --branch`.
4. Identificar dependencias externas afectadas.
5. Definir como se va a verificar el cambio.

## Reglas generales

- Mantener cambios acotados.
- No hacer refactors masivos sin pedido explicito.
- No borrar prototipos sin autorizacion.
- No modificar datos de contacto sin validacion.
- No introducir build tools salvo decision aprobada.
- No depender de contenido invisible para explicar la propuesta.

## HTML

- Usar HTML semantico.
- Mantener un solo `h1` por pagina publicable.
- Usar botones para acciones y enlaces para navegacion.
- Agregar labels, `aria-*` o texto accesible cuando corresponda.
- No esconder informacion critica detras de animaciones.

## CSS

- Respetar el sistema visual existente.
- Evitar nuevas paletas sin razon de marca.
- Mantener responsive real en mobile y desktop.
- Revisar que no haya textos superpuestos.
- Evitar estilos inline nuevos salvo ajustes puntuales.

## JavaScript

- Evitar aumentar el JavaScript inline.
- Manejar errores cuando una dependencia externa pueda fallar.
- No bloquear scroll o contenido si el loader falla.
- Evitar `alert()` en experiencias productivas.
- Evitar logs de debug en produccion.

## Accesibilidad

Todo cambio visual o interactivo debe revisar:

- Navegacion por teclado.
- Estados de foco visibles.
- `aria-expanded` en menus desplegables.
- `aria-controls` cuando aplique.
- `alt` de imagenes.
- Contraste.
- `prefers-reduced-motion`.

## Performance

- Evitar videos o imagenes nuevas sin optimizar.
- Usar lazy loading en imagenes no criticas.
- Minimizar dependencias externas.
- No cargar librerias pesadas para interacciones simples.
- Medir impacto si se agregan animaciones.

## Validacion minima

Despues de modificar:

```powershell
git status --short --branch
```

Y validar manualmente:

- Home carga.
- Loader no deja la pagina bloqueada.
- Menu mobile funciona.
- Links internos navegan.
- CTA principal abre destino correcto.
- No hay overflow horizontal evidente.

