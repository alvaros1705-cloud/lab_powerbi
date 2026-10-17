# Laboratorio Interactivo: Huella Tecnológica Empresarial con Power BI

Recurso educativo estático (HTML + CSS + JS, sin dependencias externas).

## Abrir
Abra `index.html` en un navegador moderno (doble clic). No requiere servidor.

## Estructura
- `index.html`: página principal.
- `assets/app.js`: contenido de las secciones, filtros, gráficos SVG y evaluación.
- `assets/style.css`: estilos (incluye modo oscuro e impresión).
- `assets/data.js`: los 308 registros de *Technographic Data.csv* (generado del CSV original).
- `assets/*.jpg`: capturas extraídas de la guía PDF original.

## Editar
Los textos están en `assets/app.js` (arreglos `STEPS`, `GR`, `PR`, `QZ`, etc.). Para actualizar los datos, regenere `assets/data.js` con el formato `window.DATA=[[dominio,ticker,tecnología,id,primera,última,firewall,duracion_dias,categoria(0-3)],...]`.

## Publicar en GitHub Pages
Suba la carpeta a un repositorio, en *Settings → Pages* elija la rama `main` y la carpeta raíz. Todas las rutas son relativas.

## Notas
- El progreso se guarda en `localStorage` del navegador; no se envía nada a servicios externos.
- La página es una simulación educativa con el CSV; no está conectada a Power BI Service.


Actualización (17-10-2026): se añadió selector de idioma Español/English con banderas de Colombia y Reino Unido, diseño adaptable a pantallas pequeñas, y el paso faltante para crear Huella_Tecnologica mediante Referencia. Se conservaron las demás funcionalidades del laboratorio.
