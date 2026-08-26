# 10-TEAM

## Qué va aquí

Todo lo relacionado con personas que colaboran contigo. Si trabajas solo, esta carpeta puede quedar vacía hasta que sumes a alguien.

Acá llevas:
- Roster (quién es quién)
- Carpeta por persona con: onboarding, learning path, decisiones, tareas asignadas, reviews

## Cuándo agregar algo

- Sumas a alguien al equipo (full-time, part-time, contratista, voluntario).
- Tomas una decisión sobre el equipo (promoción, cambio de rol, fin de contrato).
- Una persona del equipo cierra una semana y necesitas archivar su reporte.

## Cuándo NO agregar acá

- **Notas personales sobre relaciones.** No es lo que JARVIS necesita. Es para gestión profesional, no diario íntimo.
- **Conversaciones operativas del día a día.** Esas van por tu canal habitual (Slack, WhatsApp, email).

## Archivos globales

- **`ROSTER.md`** - lista de quién está en el equipo y su rol.
- **`reports-template.md`** - plantilla del reporte diario o semanal que pides al equipo.

## Estructura sugerida por persona

```
10-TEAM/<nombre>/
├── README.md              ← ficha de la persona
├── onboarding.md          ← qué hizo en su primera semana
├── learning-path.md       ← ruta de aprendizaje propuesta
├── decisiones.md          ← decisiones tomadas con/sobre esta persona
├── tareas-asignadas/      ← tareas activas
├── reports/               ← reportes diarios/semanales archivados
└── reviews/               ← reviews formales periódicos
```

## Ejemplo genérico

`10-TEAM/colaborador-x/README.md`

```
# colaborador-x

- **Rol:** Frontend dev (junior)
- **Inicio:** YYYY-MM-DD
- **Modalidad:** part-time remoto
- **Stack que maneja:** HTML/CSS/JS, Vue básico
- **Stack que está aprendiendo:** Vue 3 + Nuxt
- **Proyectos asignados:** proyecto-X (frontend)
- **Reporte:** diario, antes de las 18:00
```

## Convención

Nombre de carpeta en kebab-case con primer nombre o seudónimo. NO uses datos personales identificables (apellidos completos, IDs) en nombres de carpetas.
