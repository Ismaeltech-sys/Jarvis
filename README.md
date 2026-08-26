# Jarvis — Visor del Cerebro Digital

Visor educativo/de auditoría de la estructura de un vault JARVIS (metodología numerada 00→13, tipo PARA/Zettelkasten).

Un único archivo `index.html`, sin build step ni backend. Los datos del vault están embebidos como objeto JS dentro del propio archivo (no hace `fetch`), por lo que funciona tanto abierto con doble clic (`file://`) como servido por GitHub Pages (`https://`). Depende únicamente de CDNs públicos: Tailwind Play, Google Fonts, Vis.js y Lucide Icons.

## Desarrollo local

Abre `index.html` directamente en el navegador. No requiere instalación.

## Publicación

Servido vía GitHub Pages desde la rama `main`, raíz del repo.
