# Skill: process-inbox

## Cuándo se invoca

El usuario dice "procesa el inbox", "limpiemos 00-INBOX".

## Qué hace

Revisa cada archivo de `00-INBOX/` y propone destino. No mueve nada sin confirmación.

## Pasos

1. Lista todos los archivos en `00-INBOX/`.
2. Para cada archivo:
   - Lee el contenido.
   - Propón destino: `01-CAPTURES/<tipo>/`, `06-PROJECTS/<proyecto>/`, `02-CONNECTIONS/`, o `borrar`.
   - Justifica en una línea por qué.
3. Pide confirmación batch al usuario antes de mover.
4. Al confirmar, ejecuta los movimientos.

## Output esperado

- `00-INBOX/` vacío o reducido a lo que el usuario decidió conservar.
- Archivos reubicados en sus carpetas finales.

## Restricciones

- Nunca borrar sin confirmación explícita.
- Si dos archivos parecen conectar, proponer `02-CONNECTIONS/` antes de moverlos sueltos.
