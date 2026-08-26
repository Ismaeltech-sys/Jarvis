# 05-CLAUDE

## Qué va aquí

El cerebro del vault desde la perspectiva de la IA. Reglas globales, skills personales, contexto que el asistente debe cargar antes de operar.

Esta carpeta es para tu asistente, no para ti. Tú escribes acá lo que la IA debe saber.

## Subcarpetas

- **`context/`** - contexto que la IA debe conocer (sobre ti, sobre tu mercado, sobre tu forma de trabajar).
- **`skills/`** - workflows propios del vault. Procedimientos paso a paso que la IA debe ejecutar cuando los invocas.

## Cuándo agregar algo

- Notaste que la IA mete la pata con cierto tema. Escribes en `context/` la corrección.
- Repites el mismo flujo tres veces (procesar inbox, arrancar proyecto, cerrar proyecto). Conviértelo en un skill en `skills/`.
- Cambias tu forma de pensar sobre algo y la IA debe actualizar su modelo. Actualizas `CLAUDE.md` o un archivo de contexto.

## Cuándo NO agregar acá

- **Knowledge técnico reusable.** Va a `07-KNOWLEDGE/`.
- **Credenciales o datos sensibles.** Nunca. Van a `09-CREDENTIALS/` como referencia.
- **Cosas de un proyecto específico.** Van a `06-PROJECTS/<proyecto>/`.

## Ejemplo de skill genérico

`skills/start-project.md`

```
# Skill: start-project

Cuando el usuario dice "arranquemos un proyecto", ejecuto:

1. Lee 06-PROJECTS/REGISTRY.md para ver proyectos previos.
2. Lee 08-SKILLS/INVENTORY.md para ver skills disponibles.
3. Pregunta:
   - Nombre del proyecto
   - Stack técnico
   - Audiencia
   - Resultado esperado
4. Crea 06-PROJECTS/<nombre>/README.md con la respuesta.
5. Actualiza 06-PROJECTS/REGISTRY.md.
```

## Convención

El `CLAUDE.md` raíz del vault hace referencia a archivos de esta carpeta usando `@05-CLAUDE/skills/<nombre>.md`. Mantén nombres en kebab-case.
