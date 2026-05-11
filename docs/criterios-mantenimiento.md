# Criterios de mantenimiento del portal

## Principios básicos

1. No modificar herramientas en producción desde este portal.
2. Mantener cada aplicación independiente.
3. Documentar siempre cambios relevantes.
4. Diferenciar claramente entre producción, pruebas y prototipo.
5. No subir claves, contraseñas ni datos de pacientes.
6. No subir información clínica identificable.
7. Revisar enlaces periódicamente.
8. Añadir nuevas herramientas solo cuando estén validadas para su incorporación al portal.

## Recomendaciones operativas

- Actualizar metadatos de cada herramienta tras revisiones funcionales/técnicas.
- Comprobar la coherencia entre `index.html` y los `README.md` en `apps/`.
- Mantener el portal como capa de acceso y documentación, no como entorno de ejecución de aplicaciones externas.
