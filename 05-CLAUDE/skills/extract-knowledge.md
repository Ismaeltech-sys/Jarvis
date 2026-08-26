# Skill: extract-knowledge

## Cuándo se invoca

El usuario dice "cerremos este proyecto", "extrae knowledge", "esto ya terminó".

## Qué hace

Al cerrar un proyecto, sube lo genérico y reusable a `07-KNOWLEDGE/` para que futuros proyectos lo encuentren.

## Pasos

1. Lee `06-PROJECTS/<proyecto>/` completo.
2. Identifica qué decisiones, patrones, plantillas y aprendizajes son específicos del proyecto vs cuáles son reusables.
3. Para cada elemento reusable:
   - Decide a qué subcarpeta de `07-KNOWLEDGE/` pertenece.
   - Crea o actualiza el archivo correspondiente.
   - Escribe la versión genérica, sin datos del proyecto original.
4. En `06-PROJECTS/<proyecto>/README.md`, anota qué se extrajo y dónde quedó.
5. Marca el proyecto como cerrado en `06-PROJECTS/REGISTRY.md`.

## Output esperado

- Uno o varios archivos nuevos/actualizados en `07-KNOWLEDGE/`.
- Notas en el README del proyecto cerrado.
- Estado actualizado en el REGISTRY.

## Restricciones

- No copiar datos del proyecto original (clientes, montos, fechas). Solo el patrón.
- Si dudas si algo es genérico o específico, pregunta antes de extraer.
