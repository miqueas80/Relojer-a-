# El Taller del Tiempo — Relojería de las Maravillas

Juego educativo de relojería, inspirado en el mundo literario de Alicia en el país de las maravillas.

## Estado del proyecto
- La página `index.html` contiene la escena cinematográfica de la mesa del té y cinco reparaciones interactivas.
- Las voces originales de Narrador, Conejo, Sombrerero, Gato y Reina están **preparadas** para integrarse, pero los MP3 todavía no están cargados en este repositorio.
- Los audios de la Oruga (`Oruga.mp3`, `Oruga2.mp3`) y el coro final (`Todos.mp3`) están pendientes.
- Mientras falten audios, los diálogos continúan como subtítulos, sin voz sintética.

## Incorporar las voces
Subí los MP3 a la carpeta `audio/` con estos nombres exactos:
`Narrador.mp3`, `Conejo.mp3`, `Conejo2.mp3`, `Sombrerero.mp3`, `Sombrerero2.mp3`, `Gato.mp3`, `Gato2.mp3`, `Reina.mp3`, `Reina2.mp3`.

Después se pueden incorporar `Oruga.mp3`, `Oruga2.mp3` y `Todos.mp3`, actualizando las tres entradas `null` del arreglo `AUDIO_CLIPS` en `index.html`.

## Probar y publicar
Abrí `index.html` localmente. Para publicar en GitHub Pages, en este repositorio elegí **Settings → Pages → Deploy from a branch → main → /(root)**.

## Derechos
La edición pública no contiene los clips de películas comerciales usados como referencia privada. Antes de publicar audios, verificá que contás con autorización para distribuirlos. Las reparaciones están simplificadas con fines didácticos.
