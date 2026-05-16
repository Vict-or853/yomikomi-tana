# Contribuir a YomiKomi Tana

Gracias por querer mejorar YomiKomi Tana. Para que el repositorio siga limpio, cada cambio debería tener un objetivo concreto y poder revisarse sin contexto extra.

## Flujo recomendado

1. Abre o revisa un issue antes de empezar si el cambio afecta comportamiento.
2. Crea una rama desde `main` usando un nombre descriptivo.
3. Haz commits pequeños con mensajes claros.
4. Actualiza `CHANGELOG.md` si el cambio afecta a usuarios.
5. Abre un pull request con capturas o notas de prueba.

## Nombres de ramas

- `feature/nombre-corto` para funciones nuevas.
- `fix/nombre-corto` para bugs.
- `docs/nombre-corto` para documentación.
- `release/vX.Y.Z` para preparar una versión.

## Mensajes de commit

Usa una convención corta:

```text
tipo: resumen breve
```

Tipos sugeridos: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `build`, `chore`.

Ejemplos:

```text
feat: add kindle paperwhite profile
fix: preserve rtl metadata in epub output
docs: improve release instructions
```

## Antes de abrir un PR

- Verifica que la app o la web abra correctamente.
- Evita subir archivos privados, tomos de manga, builds pesados o instaladores fuera de Releases.
- Incluye pasos de prueba manual cuando no haya tests automáticos.
