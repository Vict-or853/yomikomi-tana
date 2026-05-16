# YomiKomi Tana

YomiKomi Tana es una aplicación de escritorio gratuita y 100% offline para convertir, recortar y organizar manga, cómics y webtoons locales en formatos listos para e-readers y tablets.

[Descargar última versión](https://github.com/Vict-or853/yomikomi-tana/releases) | [Reportar un bug](https://github.com/Vict-or853/yomikomi-tana/issues/new?template=bug_report.yml) | [Apoyar en Ko-fi](https://ko-fi.com/vict_or853)

![Interfaz de YomiKomi Tana](assets/yomikomi-main.png)

## Funciones principales

| Función | Para qué sirve |
| --- | --- |
| Auto-crop inteligente | Recorta márgenes blancos o negros para aprovechar mejor la pantalla. |
| División de páginas dobles | Separa escaneos horizontales en páginas verticales. |
| Modo webtoon | Convierte tiras largas en páginas individuales. |
| Modo manga RTL | Genera EPUB con lectura de derecha a izquierda. |
| Perfiles de dispositivo | Ajusta salida para Kindle, Kobo y tablets. |
| Procesamiento offline | Tus archivos se quedan en tu equipo. |

## Descarga

1. Entra a [Releases](https://github.com/Vict-or853/yomikomi-tana/releases).
2. Descarga el instalador de la versión más reciente.
3. Ejecuta la app en Windows 10 o Windows 11.

Windows puede mostrar una advertencia de SmartScreen en aplicaciones nuevas. Descarga siempre desde el repositorio oficial.

## Formatos

Entradas compatibles: carpetas, `.zip`, `.rar`, `.cbz`, `.cbr`.

Salidas compatibles: `.epub`, `.cbz`.

## Privacidad

YomiKomi Tana procesa los archivos localmente. No necesitas subir tu biblioteca a la nube para convertirla.

## Sitio web

La página del proyecto vive en `index.html` y se publica con GitHub Pages desde la rama principal.

Para verla localmente:

```powershell
python -m http.server 8001 --bind 127.0.0.1
```

Después abre `http://127.0.0.1:8001/`.

## Comunidad

Los reportes de bugs, ideas de funciones y mejoras de documentación son bienvenidos. Al abrir un issue, incluye versión de la app, sistema operativo, pasos para reproducir y capturas cuando aplique.

## Mantenimiento

El repositorio incluye plantillas de issues, plantilla de pull request, changelog, configuración de GitHub Pages y una guía corta de flujo de trabajo en [docs/git-workflow.md](docs/git-workflow.md).

## Licencia

YomiKomi Tana se distribuye como freeware. El código, los textos y los assets conservan los derechos de su autor salvo que se indique una licencia diferente.
