# AGENTS.md

# hernysgodoy.com

## Proyecto

Este repositorio contiene el sitio web oficial de hernysgodoy.com.

La web forma parte del sistema comercial y de posicionamiento de Herny Godoy.

No debe tratarse únicamente como un portfolio de diseño o desarrollo web.

El posicionamiento principal es el de consultor estratégico que integra negocio, comunicación, tecnología, automatización e inteligencia artificial para diseñar e implementar sistemas de crecimiento y eficiencia.

---

## Fuente principal de producción

Actualmente la página principal activa es:

`index.html`

No asumir que otros archivos HTML de la raíz forman parte de producción.

Antes de modificar un archivo distinto de `index.html`, verificar su función.

---

## Antes de realizar una tarea

Leer cuando corresponda:

- `docs/PROJECT_CONTEXT.md`
- `docs/ARCHITECTURE.md`
- `docs/STACK.md`
- `docs/DESIGN_SYSTEM.md`
- `docs/SEO_GUIDELINES.md`
- `docs/CONTENT_GUIDELINES.md`
- `docs/DEVELOPMENT_RULES.md`
- `docs/DEPLOYMENT.md`

---

## Reglas generales

1. No modificar archivos sin entender primero su función.

2. No modificar archivos legacy, backups o prototipos salvo solicitud explícita.

3. No introducir frameworks, librerías o dependencias nuevas sin autorización.

4. Respetar el stack existente salvo que la tarea indique una migración.

5. Mantener compatibilidad responsive.

6. Mantener o mejorar accesibilidad.

7. Mantener o mejorar SEO técnico y semántico.

8. No eliminar animaciones o interacciones existentes sin justificarlo.

9. Evitar duplicación de código cuando pueda resolverse de forma razonable sin sobrearquitectura.

10. No almacenar credenciales, tokens, contraseñas o API keys en el repositorio.

11. No modificar configuración de hosting ni producción sin autorización explícita.

12. Antes de realizar cambios estructurales, explicar brevemente el plan.

13. Después de cada tarea informar:

- archivos modificados;
- cambios realizados;
- pruebas efectuadas;
- posibles riesgos o pendientes.

14. Ejecutar `git diff` o equivalente antes de considerar terminada una modificación.

15. No realizar commits ni push salvo solicitud explícita.

---

## Criterio de implementación

Priorizar:

- claridad;
- mantenibilidad;
- performance;
- accesibilidad;
- SEO;
- compatibilidad responsive;
- coherencia visual;
- simplicidad técnica.

Evitar sobreingeniería.

---

## Cambios comerciales o de contenido

No inventar:

- propuestas de valor;
- precios;
- servicios;
- datos de contacto;
- claims;
- métricas;
- testimonios;
- posicionamiento comercial.

Consultar `docs/PROJECT_CONTEXT.md` y `docs/CONTENT_GUIDELINES.md`.

Si existe una contradicción, detener la modificación y señalarla.

---

## Seguridad Git

La rama `main` representa el estado estable del proyecto.

El trabajo de preparación inicial de Codex se realiza actualmente sobre:

`codex/setup`

No cambiar de rama, hacer merge, push, reset destructivo o reescribir historial sin autorización explícita.
