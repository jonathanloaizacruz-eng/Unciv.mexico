# Unciv.mexico

Mod de Unciv para la civilización de México.

## Descripción

Este mod añade la civilización de México al juego Unciv, con Porfirio Díaz como líder. Incluye unidades exclusivas para cada época, edificios con temática mexicana, recursos estratégicos y sonidos tradicionales.

## Estructura

- `Jsons/Nations.json`: Definición de la civilización México.
- `Jsons/Units.json`: Unidades exclusivas mexicanas.
- `Jsons/Buildings.json`: Edificios temáticos.
- `Jsons/TileImprovements.json`: Mejoras de terreno (Chinampas).
- `Jsons/Resources.json`: Recursos estratégicos únicos.
- `atlas/`: Imágenes y atlas para unidades y edificios (agregar manualmente).
- `background.png`: Imagen de fondo del mod con la bandera de México.
- `modInfo.json`: Metadata estándar del mod.

## Instalación en Unciv (PC y Android)

### Opción 1: Desde GitHub (Recomendado)
1. Abre Unciv en tu dispositivo.
2. Ve al menú principal > Mods.
3. Selecciona "Download mod" o "Install from URL".
4. Pega esta URL: `https://raw.githubusercontent.com/jonathanloaizacruz-eng/Unciv.mexico/main/Unciv.mexico.zip`
5. Descarga e instala el mod.
6. Reinicia Unciv y activa "Mexico" en el menú de mods.

> Nota: este ZIP se preparó para que la app pueda descargarlo directamente con el mod en la raíz del paquete.

### Opción 2: Instalación Manual
1. Descarga el repositorio como ZIP desde GitHub.
2. Extrae la carpeta `Unciv.mexico`.
3. Copia la carpeta a la ubicación de mods de Unciv:
   - **Android**: Usa un explorador de archivos para copiar a `Android/data/com.unciv.app/files/mods/` (puede requerir root o app como X-plore).
   - **PC**: Copia a `~/.unciv/mods/` (Linux/Mac) o `%USERPROFILE%\.unciv\mods\` (Windows).
4. Reinicia Unciv y activa el mod.

Asegúrate de añadir imágenes en `atlas/` y sonidos en `audio/` para una experiencia completa. El mod funciona con placeholders, pero se ve mejor con assets reales.
