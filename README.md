# Muro Digital 3D de Auspiciadores

Muro de auspiciadores en 3D: vistas Individual, En línea, Mosaico, Ajedrez, Anillo 3D y Presentación, con modo TV automático, anillos de luz por color de logo, logo del anfitrión, fondo con imágenes, QR, sonido, reporte de apariciones, temas y PIN.

Sitio publicado: https://jwilsoncruz.github.io/MuroDigital3D/

## Contenido
- `index.html` — la aplicación completa (un solo archivo).
- `config.json` — configuración que la página lee al abrir.
- `logos/` — carpeta opcional para tus logos.
- `.nojekyll` — evita que GitHub procese el sitio.
- `CHANGELOG.md` — historial de versiones.

## Publicar o actualizar
1. En el repositorio pulsa **Add file → Upload files**.
2. Arrastra todo el contenido de este zip (descomprimido) y **Commit changes**.
3. En **Settings → Pages** elige *Deploy from a branch → main / (root)*.
4. Espera 1–2 minutos y recarga con **Ctrl + F5**. Abajo a la izquierda debe verse la versión.

## Guardar cambios
1. Abre la página y edita todo en ⚙ **Configuración**.
2. Pulsa **⬇ Descargar config.json (GitHub)**.
3. Reemplaza `config.json` en el repositorio. Cualquier PC o TV que abra el enlace verá lo mismo.

Para un `config.json` liviano, copia los logos a `logos/` y usa rutas como `"img": "logos/cocacola.png"`.

## Notas
- El PIN no se exporta (el repositorio es público).
- El código QR carga su librería desde cdnjs: necesita internet.
- Los cambios hechos en la página de GitHub son temporales hasta que subas el nuevo `config.json`.
