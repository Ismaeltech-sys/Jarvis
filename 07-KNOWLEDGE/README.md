# 07-KNOWLEDGE

## Qué va aquí

Conocimiento genérico, reusable, extraído de tus proyectos. NO es donde nace el conocimiento - es donde se deposita una vez probado.

Si tienes una idea sin proyecto detrás que la valide, va a `01-CAPTURES/`, no acá. Cuando aplicaste algo en 2-3 proyectos y funcionó, ahí sí lo subes acá como knowledge.

## Cuándo agregar algo

- Cierras un proyecto y al hacer `extract-knowledge` identificas patrones reusables.
- Notas que en tres proyectos distintos resolviste el mismo problema de la misma forma.
- Tu asistente te pregunta "cómo prefieres hacer X" y te das cuenta que ya tienes una respuesta consistente.

## Cuándo NO agregar acá

- **Es solo teoría.** Sin proyecto que lo haya probado, no es knowledge tuyo todavía. Va a `01-CAPTURES/patterns/`.
- **Es muy específico de un proyecto.** Va a `06-PROJECTS/<proyecto>/`.
- **Es una credencial o secreto.** Va a `09-CREDENTIALS/` como referencia.

## Subcarpetas sugeridas

Organiza por dominio. Algunas categorías comunes:

- `stack-standards/` - tu stack default por tipo de proyecto
- `copywriting/` - patrones de escritura que funcionan para ti
- `design/` - decisiones de diseño reusables (paletas, tipografías, layouts)
- `deployment/` - cómo despliegas en cada plataforma
- `security/` - patrones de seguridad que aplicas siempre
- `automations/` - flujos automatizados que repites
- `frontend/` - patrones de frontend
- `patterns/` - patrones mentales transversales

Crea las que necesites. No las uses todas si no aplica.

## Ejemplo genérico

`07-KNOWLEDGE/stack-standards/internal-projects-stack.md`

```
# Stack default para proyectos internos

Para proyectos internos rápidos, el default es:

- Lenguaje: <X>
- Framework: <Y>
- Base de datos: <Z>
- Hosting: <W>

Razón: balance entre velocidad de desarrollo y costo de mantenimiento.

Cuándo cambiar el default:
- Si el proyecto tiene > 10k usuarios esperados: revisar W.
- Si el proyecto necesita real-time: revisar Y.
```

## Regla de oro

Knowledge sin caso real detrás es teoría. Antes de aceptar algo acá, exige al menos un proyecto que lo haya validado.
