# DUCK 2026

Versión actualizada del proyecto DUCK con los componentes y assets identificados en Google Drive durante 2026.

## Entrada recomendada

Abre `DUCK-2026-ACTUALIZADO.html` en un navegador. La página utiliza referencias locales a `data.js`, `app.js`, `styles.css` y a la carpeta `images` del proyecto original. La versión publicada conserva también `index.html`, `DUCK-MEGA-UNIFICADO.html`, `02-DUCK-FUSIONADO-COMPLETO.html` y `legacy-studio-console.html` como variantes de referencia.

## Contenido

| Archivo | Descripción |
|---|---|
| `DUCK-2026-ACTUALIZADO.html` | Variante actualizada con registro interno de build 2026. |
| `index.html` | Entrada operativa del portfolio unificado. |
| `app.js` | Renderizado, previews y comportamiento interactivo. |
| `data.js` | Datos de catálogo, servicios, estudio y equipo. |
| `styles.css` | Sistema visual y responsive. |
| `DUCK-2026-INVENTARIO-Y-PLUGINS.md` | Auditoría de assets, dependencias y plugins. |
| `DUCK-INTEGRADO-0-10.md` | Mapa funcional de niveles 0 a 10. |

## Dependencias

Las variantes existentes referencian GSAP, ScrollTrigger, ScrollToPlugin en algunas páginas y Lenis mediante CDN. Para utilizar el sitio sin conexión, esas dependencias deben descargarse y fijarse localmente. Los módulos `gsap-scroll-enhancements.js`, `musical-tools.js`, `slime-gpu-optimizer.js`, `performance-utils.js` y `material-ui-components.css` aparecen en la documentación del Drive, pero no fueron encontrados como archivos reales y no se declaran instalados.

## Assets

La carpeta `images` del Drive contiene las subcarpetas `covers`, `studio`, `VERDE` y `variants`. Esta publicación incluye el código y la documentación disponibles localmente; los assets binarios originales deben añadirse al repositorio si se desea una ejecución visual completa fuera de Google Drive.

## Estado

Esta publicación es una integración no destructiva y privada. Los originales del Drive se conservaron sin sobrescribirlos. Antes de hacer público el repositorio, revisa los datos personales, enlaces de contacto y licencias de los assets.
