# JARVIS Starter

Tu cerebro local. Una estructura de carpetas en markdown plano que te sirve como memoria entre proyectos, contexto para IA, y bitácora personal.

JARVIS no es una app. Son carpetas con archivos `.md` que abres con Obsidian, VS Code o cualquier editor. Lo importante no es la herramienta, es que la estructura te permita encontrar tu propio conocimiento meses después.

Esta estructura está pensada para que un asistente de IA (Claude Code, por ejemplo) pueda leer tu vault como contexto antes de proponerte nada.

Todas las carpetas de este repo contienen **plantillas vacías**, no datos reales — es el punto de partida antes de que las llenes con tu propio contenido.

## Visor interactivo

Este repo incluye un visor web de un único archivo (`index.html`, sin build ni backend) que audita y explica esta misma estructura de forma visual: grafo de conexiones entre carpetas, tarjetas por carpeta y un onboarding guiado.

**Míralo en vivo:** https://ismaeltech-sys.github.io/Jarvis/

## Mapa de carpetas

| Carpeta | Para qué |
|---|---|
| `00-INBOX/` | Captura cruda. Lo que llega sin procesar. |
| `01-CAPTURES/` | Captura clasificada por tipo (números, observaciones, patrones, preguntas, reacciones). |
| `02-CONNECTIONS/` | Conexiones entre capturas. Cuando dos ideas separadas se vuelven una sola tesis. |
| `03-BRIEFS/` | Briefs intermedios listos para convertirse en contenido o decisiones. |
| `04-PUBLISHED/` | Archivo de lo ya publicado. Para no repetirte y para citarte. |
| `05-CLAUDE/` | El cerebro del vault. Reglas globales del asistente, skills personales, contexto. |
| `06-PROJECTS/` | Un folder por proyecto. Caso documentado, decisiones, sesiones, pendientes. |
| `07-KNOWLEDGE/` | Conocimiento genérico reusable extraído de tus proyectos. |
| `08-SKILLS/` | Catálogo de skills/workflows que tienes disponibles. |
| `09-CREDENTIALS/` | Referencias a credenciales (los valores reales viven en tu keychain). |
| `09-FINANCE/` | Finanzas por proyecto o por entidad. |
| `10-TEAM/` | Si trabajas con gente: roster, onboarding, reviews, tareas asignadas. |
| `11-IDENTITY/` | Tu identidad: rol, voz, posicionamiento, datos base. |
| `12-DAILY/` | Bitácora diaria. Un archivo por día. |
| `13-OBLIGACIONES/` | Pagos recurrentes, servicios, suscripciones. Referencias, no montos sensibles. |

## Cómo empezar

1. **Abre el folder en Obsidian** (o tu editor de markdown preferido). Recomendado Obsidian porque ya entiende links `[[archivo]]` entre notas.
2. **Edita `CLAUDE.md` en la raíz** con tus reglas. La plantilla está vacía a propósito.
3. **Crea tu primer proyecto** en `06-PROJECTS/<tu-proyecto>/README.md`. Describe en una página qué es el proyecto, qué stack usa, qué decisiones tomaste.
4. **Captura lo primero** en `00-INBOX/`. Una idea, una observación, lo que sea. No clasifiques al inicio. Eso viene después.
5. **Cuando empieces a notar patrones**, muévelos a `01-CAPTURES/patterns/` y considera elevarlos a `07-KNOWLEDGE/` cuando sean reusables.

## Filosofía

- **Lo crudo entra por `00-INBOX/`**, no directo a su capa final.
- **`07-KNOWLEDGE/` es destino, no origen.** El conocimiento genérico se extrae de proyectos reales, no se inventa abstracto.
- **JARVIS nunca produce código.** Es solo planeación, memoria y contexto. El código vive en tus repos.
- **`05-CLAUDE/CLAUDE.md` define las reglas** que la IA debe respetar cuando lee tu vault.

## Guía completa

Esta estructura es la base. La explicación de cada decisión, cómo conectarla con Claude Code, y el flujo completo de captura está en:

https://santa-ia.com/biblioteca/jarvis-tu-cerebro-local

## Crédito

Estructura derivada del JARVIS de Miguel Santa - [@santaia.lab](https://instagram.com/santaia.lab).

Si te sirve, te invito a contar cómo la estás usando. Y si la modificas para algo distinto, mejor.
