# CLAUDE.md - Reglas de mi vault

Este archivo lo lee tu asistente de IA cada vez que trabaja sobre este vault. Personalízalo. Lo que escribas acá orienta a la IA antes de hacer cualquier propuesta.

---

## Identidad

> Reemplaza este bloque con tu identidad real.

- Mi nombre:
- Mi rol principal:
- En qué estoy trabajando hoy:
- Mi voz (cómo escribo):

## Reglas de colaboración

Lista de cosas que la IA debe respetar al asistirte. Ejemplos para personalizar:

- Si dudo entre dos opciones, pregunto antes de actuar.
- Si una operación es destructiva (borrar archivos, force push, sobrescribir), pido confirmación.
- No invento datos. Si no encuentro la información en este vault, lo digo claro y pregunto.
- Antes de proponer un stack técnico, leo `07-KNOWLEDGE/stack-standards/` si existe.

## Reglas de seguridad

- Nunca leer ni escribir archivos `.env` del vault.
- Los secretos (tokens, API keys, passwords) viven en macOS Keychain o equivalente. En este vault solo van **referencias**, nunca valores.
- `09-CREDENTIALS/` contiene metadatos de credenciales, no las credenciales mismas.

## Reglas de escritura

> Si vas a usar la IA para redactar texto en tu nombre, dile cómo suenas:

- Frases cortas o largas:
- Palabras que evitas:
- Tono (formal, casual, técnico, didáctico):
- Idioma principal:

## Cómo se actualiza este vault

1. Capturas crudas entran por `00-INBOX/`.
2. Cuando proceses el inbox, mueve lo útil a `01-CAPTURES/` (clasificado por tipo).
3. Cuando encuentres un patrón repetido en varias capturas, escríbelo en `02-CONNECTIONS/`.
4. Cuando algo merezca volverse pieza de contenido o decisión formal, hazlo `03-BRIEFS/`.
5. Cuando publiques algo (post, video, decisión tomada), archívalo en `04-PUBLISHED/`.
6. **Al cerrar un proyecto en `06-PROJECTS/`**, extrae lo genérico a `07-KNOWLEDGE/`.
7. **La bitácora diaria en `12-DAILY/`** es el registro narrativo del día. Un archivo por fecha, formato `YYYY-MM-DD.md`.

## Carpetas que la IA debe consultar antes de proponer

- Proyecto nuevo: `06-PROJECTS/REGISTRY.md` + `08-SKILLS/INVENTORY.md` + `07-KNOWLEDGE/`.
- Preguntas técnicas: `07-KNOWLEDGE/` antes de improvisar.
- Cosas de equipo: `10-TEAM/`.
- Pagos o servicios: `13-OBLIGACIONES/` y `09-FINANCE/`.

## JARVIS no produce código

Este vault es para planeación, memoria, contexto y knowledge. El código real vive en tus repos de proyecto, no aquí. Si pides "construir algo", la IA debe entregar:

- Un README de subproyecto
- Un `plan.md` detallado
- Decisiones de stack documentadas
- Prompts para que una sesión nueva ejecute en el repo correcto

Nunca archivos `.py`, `.vue`, `.ts`, `.swift` dentro de este vault.
