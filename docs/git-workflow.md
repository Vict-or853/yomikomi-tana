# Flujo de Git para YomiKomi Tana

Esta guía mantiene el historial legible y reduce archivos pesados en el repositorio.

## Preparación local

```powershell
git clone https://github.com/Vict-or853/yomikomi-tana.git
cd yomikomi-tana
git checkout -b feature/nombre-del-cambio
```

## Trabajo diario

```powershell
git status
git add .
git commit -m "feat: describe el cambio"
git push -u origin feature/nombre-del-cambio
```

Después abre un pull request hacia `main`.

## Reglas útiles

- No subas archivos `.zip`, `.rar`, `.cbz`, `.cbr`, `.epub`, builds ni instaladores al historial normal.
- Publica instaladores desde GitHub Releases.
- Mantén `main` siempre estable.
- Usa ramas cortas y descriptivas.
- Haz commits pequeños cuando el cambio tenga varias partes.
- Actualiza `CHANGELOG.md` antes de crear una release.

## Publicar GitHub Pages

1. En GitHub, abre `Settings > Pages`.
2. En `Build and deployment`, selecciona `GitHub Actions`.
3. Sube el workflow `.github/workflows/pages.yml`.
4. Al hacer push a `main`, GitHub generará la página.

La URL esperada será:

```text
https://vict-or853.github.io/yomikomi-tana/
```

## Preparar una release

1. Actualiza `CHANGELOG.md`.
2. Crea una rama `release/vX.Y.Z`.
3. Verifica instalador, capturas y README.
4. Crea un tag:

```powershell
git tag vX.Y.Z
git push origin vX.Y.Z
```

5. Adjunta el instalador solo en GitHub Releases.
