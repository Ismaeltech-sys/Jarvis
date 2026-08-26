# Skill: start-project

## Cuándo se invoca

El usuario dice "arranquemos un proyecto", "vamos a empezar X", "nuevo proyecto".

## Qué hace

Antes de crear cualquier carpeta, valida que no estés duplicando un proyecto previo y propone reutilización de skills + knowledge existentes.

## Pasos

1. Lee `06-PROJECTS/REGISTRY.md`. Si hay proyectos parecidos al que el usuario propone, menciónalos y pregunta si quiere fusionar o seguir aparte.
2. Lee `08-SKILLS/INVENTORY.md`. Propón qué skills aplican al proyecto nuevo.
3. Lee `07-KNOWLEDGE/` (subcarpetas relevantes). Lista qué conocimiento ya extraído podría aplicar.
4. Pregunta lo mínimo necesario:
   - Nombre del proyecto (kebab-case)
   - Stack o herramientas que va a usar
   - Audiencia o usuario final
   - Resultado esperado (1 frase)
5. Crea `06-PROJECTS/<nombre>/README.md` con esa info.
6. Agrega entrada nueva en `06-PROJECTS/REGISTRY.md`.

## Output esperado

- `06-PROJECTS/<nombre>/README.md` creado
- Entrada en `06-PROJECTS/REGISTRY.md` actualizada

## Restricciones

- No asumir el stack. Preguntar siempre.
- No crear subcarpetas dentro del proyecto antes de saber qué necesita.
- Si el usuario duda entre dos nombres, pregunta. No elegir por él.
