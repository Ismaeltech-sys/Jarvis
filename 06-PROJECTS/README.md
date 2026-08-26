# 06-PROJECTS

## Qué va aquí

Una carpeta por proyecto. Cada proyecto vive en `06-PROJECTS/<nombre-kebab-case>/` y contiene todo el contexto necesario para retomarlo meses después: decisiones, sesiones, pendientes, recursos, audiencia.

JARVIS no produce código. **El código del proyecto vive en otro repo.** Acá vive la planeación, las decisiones, el contexto.

## Cuándo agregar un proyecto

- Vas a invertir más de 1 semana de trabajo en algo.
- Tiene un resultado tangible esperado.
- Vas a tomar decisiones que querrás recordar después.

## Cuándo NO crear proyecto

- **Es una tarea suelta de un día.** Va a `12-DAILY/` o `00-INBOX/`.
- **Es exploración sin compromiso.** Va a `01-CAPTURES/` o `02-CONNECTIONS/`.

## Estructura sugerida por proyecto

```
06-PROJECTS/<nombre>/
├── README.md              ← qué es el proyecto, stack, resultado esperado
├── decisiones.md          ← log de decisiones importantes con fecha y razón
├── pendientes.md          ← qué falta hacer
├── sesiones/              ← bitácora de sesiones de trabajo
├── recursos.md            ← links útiles, refs, inspiración
└── subproyectos/          ← si el proyecto se divide en partes
```

## Archivos globales

- **`REGISTRY.md`** - índice de todos los proyectos con estado (activo, pausado, cerrado).

## Ejemplo genérico

`06-PROJECTS/mi-saas-de-prueba/README.md`

```
# mi-saas-de-prueba

estado: activo
inicio: 2026-03-15
stack: Next.js + Postgres + Stripe
repo: github.com/user/mi-saas
audiencia: freelancers que cobran por hora
resultado esperado: cobrar el primer cliente antes de Q3
```

## Convención de naming

`<descriptor-en-kebab-case>` - sin espacios, sin mayúsculas, sin números al inicio.
