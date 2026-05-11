# herramientasfarmacia

Portal central de acceso, documentación y mantenimiento de herramientas digitales del Servicio de Farmacia Hospitalaria.

## Alcance de esta primera fase

Este repositorio **solo** incluye referencias para:

1. PIDEFAR
2. Guardias Farmacia
3. Sesiones Clínicas

No se incorporan en esta fase otras aplicaciones.

## Qué es este repositorio

Este repositorio es un **hub web estático** para:

- Organizar el acceso a herramientas del servicio.
- Centralizar documentación mínima de cada herramienta.
- Facilitar el mantenimiento institucional.

## Qué NO es este repositorio

- No es una macroaplicación.
- No sustituye ni fusiona las herramientas existentes.
- No modifica el código de producción de aplicaciones externas.

## Estructura actual

- `index.html`: página principal del portal.
- `styles.css`: estilos del portal.
- `apps/`: fichas documentales de cada herramienta.
- `docs/`: guías de uso y criterios de mantenimiento.
- `assets/`: espacio para recursos estáticos (actualmente sin contenido funcional).

## Cómo añadir una nueva herramienta en el futuro

1. Crear carpeta en `apps/` con nombre normalizado (`kebab-case`).
2. Añadir `README.md` siguiendo la plantilla existente.
3. Añadir una tarjeta en `index.html` dentro de la sección temática que corresponda.
4. Actualizar enlaces y estado de la herramienta.
5. Revisar `docs/criterios-mantenimiento.md` antes de publicar.

## Cómo actualizar enlaces

En `index.html`, cada tarjeta contiene enlaces con `href="#"` y comentarios HTML indicando el punto de sustitución. Reemplazar únicamente `#` por la URL oficial cuando esté validada.

## Publicación con GitHub Pages

1. Ir a **Settings → Pages** en GitHub.
2. En **Build and deployment**, seleccionar **Deploy from a branch**.
3. Elegir rama (por ejemplo, `main`) y carpeta `/ (root)`.
4. Guardar cambios y esperar la URL pública de GitHub Pages.

## Mantenimiento documental

- Mantener actualizados los `README.md` de `apps/`.
- Registrar cambios relevantes en los documentos de `docs/`.
- Revisar de forma periódica la vigencia de enlaces y estados.
