# 00-INBOX

## Qué va aquí

Captura cruda sin procesar. Todo lo que llega y no sabes dónde clasificar todavía.

## Cuándo agregar algo

- Acabas de tener una idea y no quieres perderla. La sueltas acá.
- Leíste algo, viste un video, oíste a alguien decir algo que te sonó relevante. Lo dejas acá con la fuente.
- No tienes claridad de qué carpeta es. Default: inbox.

## Cuándo NO agregar acá

- **Cuando ya sabes a qué proyecto pertenece.** Va directo a `06-PROJECTS/<proyecto>/`.
- **Cuando ya es una pieza terminada.** Va a `04-PUBLISHED/`.
- **Cuando es bitácora del día.** Va a `12-DAILY/YYYY-MM-DD.md`.

## Ejemplo genérico

`idea-newsletter-mensual.md`

```
fecha: 2026-05-18
fuente: charla con amigo

Idea: armar un newsletter mensual de los aprendizajes que extraje
de mis proyectos del mes. Formato: 5 bullets max.

Pendiente: validar si Substack o ConvertKit.
```

## Convención de naming

`<descriptor-corto>.md` — sin fechas en el nombre. La fecha va dentro del archivo.

## Limpieza

Una vez por semana, procesa el inbox. Decide para cada archivo:
- Mover a `01-CAPTURES/<tipo>/`
- Mover a `06-PROJECTS/<proyecto>/`
- Mover a `02-CONNECTIONS/` si conecta con otra captura previa
- Borrar si ya no aplica
