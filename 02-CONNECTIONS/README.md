# 02-CONNECTIONS

## Qué va aquí

Conexiones explícitas entre dos o más capturas. Cuando notas que dos cosas que registraste por separado en realidad apuntan al mismo lugar.

## Cuándo agregar algo

- Notas que dos `patterns/` distintos tienen la misma raíz.
- Una `question/` se respondió por un `number/` registrado meses después.
- Tres `observations/` de proyectos distintos describen lo mismo desde ángulos distintos.

## Cuándo NO agregar acá

- **Cuando es una sola captura aislada.** Va a `01-CAPTURES/`.
- **Cuando ya es una tesis lista para publicar.** Va a `03-BRIEFS/`.

## Ejemplo genérico

`conexion-onboarding-feedback-loop.md`

```
fecha: 2026-05-10

Conecta:
- 01-CAPTURES/patterns/usuarios-abandonan-en-onboarding.md
- 01-CAPTURES/observations/soporte-pregunta-recurrente.md
- 01-CAPTURES/numbers/churn-q1-vs-q2.md

Tesis emergente: el onboarding no falla por flujo, falla por
ausencia de un primer "click feliz" antes del paso 4.

Implicación: prototipar un quick-win en paso 2 antes de tocar
el formulario del paso 4.

Próximo paso: subir a 03-BRIEFS/ si después de 2 semanas
sigue pareciendo cierto.
```

## Convención

Cada conexión cita rutas explícitas a las capturas que conecta. Si una conexión no tiene al menos dos rutas, no es conexión.
