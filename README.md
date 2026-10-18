# El Taller del Tiempo — Edición escolar cinematográfica

Proyecto educativo interactivo basado en el universo literario de Alicia en el País de las Maravillas.

## Contenido de la rama main
- `index.html`: escena cinematográfica de la mesa del té, nueve intervenciones con voces propias ya enlazadas, cinco reparaciones educativas y reproductor para los dos videos de referencia.
- `audio/`: nueve MP3 que ya están subidos y enlazados en el código.
- `media/`: **pendiente de cargar seis archivos multimedia**, listados abajo. Los controles de video mostrarán un aviso hasta completar la carga. Se puede entrar directamente a la historia y jugar.

## Para terminar de subir la edición escolar

Descargá el paquete **el_taller_del_tiempo_presentacion_escolar_cine.zip** disponible en el chat y extraélo. En GitHub, entrá a la carpeta `media/` de la rama `main`, elegí **Add file → Upload files** y seleccioná estos seis archivos desde la carpeta `taller_del_tiempo_edicion_escolar/media/`:

- `referencia_uno.mp4` — prólogo breve 1
- `referencia_dos.mp4` — prólogo breve 2
- `pelicula_uno_completa.mp4` — montaje completo 1
- `pelicula_dos_completa.mp4` — montaje completo 2
- `poster_uno.jpg` — imagen de portada 1
- `poster_dos.jpg` — imagen de portada 2

**No vuelvas a subir los nueve MP3**: ya están correctamente guardados en `audio/`.

Si GitHub no permite cargar todos juntos, elegí archivos de a uno. Confirmá el commit en `main`. Los nombres y las mayúsculas deben coincidir.

## Audios pendientes

Faltan `audio/Oruga.mp3`, `audio/Oruga2.mp3` y opcionalmente `audio/Todos.mp3`. Las líneas sin audio quedan subtituladas.

## GitHub Pages
En **Settings → Pages → Build and deployment** seleccioná **Deploy from a branch**, rama `main`, carpeta `/(root)`. La URL esperada será `https://miqueas80.github.io/Relojer-a-/` una vez activado y completado el despliegue. No se ha verificado que esté publicado.

## Aviso sobre medios de películas
Los videos provienen de películas ajenas. El uso en una actividad escolar y la redistribución pública en GitHub son situaciones distintas; poné el repositorio privado antes de subir los videos si no tenés autorización de distribución pública. Cambiar a privado después de publicarlos no deshace copias o accesos anteriores.


## Mejora cinematográfica de producción — 18/10/2026
- Cámara de escenario 2,5D que encuadra a cada personaje durante sus intervenciones.
- Escenografía más profunda, iluminación, objetos animados, gestos de boca ilustrativos y parpadeos.
- Controles de historia: anterior/siguiente, modo de movimiento reducido, doblaje y saltar a la pregunta final.
- Instrucciones situacionales en la mesa de trabajo y botón para ampliar el reloj.
- Las nueve voces y seis recursos de video/imagen que ya estaban cargados se mantienen en sus rutas.
- Regresión superada: cinco relojes reparables, pruebas de interfaz escritorio/móvil sin errores JavaScript observados.

**Pendiente de producción de alta fidelidad:** modelado/rig artístico avanzado, sincronización labial real por audio y mezcla cinematográfica. No confundir la animación de boca actual con lipsync real.


---

## Producción cinematográfica V3 — 18/10/2026
# El Taller del Tiempo — Pase de producción cinematográfica V3

Puesta en escena de cinco personajes en la mesa del té y cinco reparaciones educativas.

## Cambios realizados
- Boca guiada por la **envolvente de amplitud** real de los nueve MP3 originales (50 ms por muestra); cuando hay silencio, el personaje deja de mover la boca. Esto **no equivale a sincronización fonética por visemas**.
- Control de pista con cronómetro de reproducción del diálogo.
- Banda sonora generativa original opcional, activada expresamente por el espectador, con volumen reducido al hablar.
- Iluminación dramática por personaje, luz volumétrica simulada y transición visual de la mesa al taller.
- Conservados los cinco juegos y los 9 MP3 y 6 medios que ya estaban alojados.
- Los archivos Oruga.mp3, Oruga2.mp3 y Todos.mp3 se usarán automáticamente si se suben a audio/; mientras falten, se mantienen subtítulos.

## Limitaciones
Las ilustraciones siguen siendo 2.5D y la animación de boca detecta energía, no fonemas ni expresión actoral real. No equivale a una película 3D profesional.

## Modo de exhibición
El botón «⛶ Proyección» abre la escena a pantalla completa en navegadores compatibles. Los subtítulos continúan visibles y podés usar flechas del teclado para retroceder o avanzar.

## Rediseño visual inmersivo V4 · 18/10/2026
- Portada panorámica original con acceso directo a la historia o a los videos de referencia.
- Teatro de conversaciones a pantalla ancha con personajes escalonados en perspectiva, encuadres por interlocutor y un primer plano ilustrado para cada voz.
- Subtítulos dentro del encuadre, controles accesibles y modo de movimientos reducidos.
- Banco de relojería ambientado con luz dramática y superficie de taller, conservando todas las mecánicas anteriores.
- La ilustración de ambientación se incluye directamente en el HTML: no requiere subir nuevos archivos para verse en GitHub Pages.
- Las pistas multimedia existentes se mantienen en `audio/` y `media/`.
- Rama de restauración: `backup/pre-visual-overhaul-v4-2026-10-18`.

**Alcance artístico:** la portada es una ilustración conceptual y los actores siguen siendo muñecos SVG animados. Los primeros planos y la animación de boca mejoran la dirección de escena, pero no equivalen a animación cinematográfica fotorrealista o sincronización exacta de fonemas.


## Director's Cut V5 — 18/10/2026

**Nueva escena interactiva, conservando las cinco reparaciones.**

- Ilustración panorámica del bosque incorporada **dentro de index.html** para evitar que falte en GitHub Pages.
- Atrezo reactivo según personaje: reloj de bolsillo, taza con vapor, partículas de la Oruga, sonrisa del Gato y corazón real de la Reina.
- Planos de cámara y reacciones visuales del elenco según las 12 intervenciones originales; subtítulos cinematográficos dentro del encuadre.
- Transición de reloj hacia el primer encargo después de pulsar «Sí, acepto»; la opción de movimiento reducido se respeta.
- Banco de reparación ampliado a una columna principal en escritorio y controles accesibles en móvil.
- Los MP3 y MP4 existentes se conservan. **No se inventó ningún audio nuevo**. Oruga y coro siguen pendientes.

**Pruebas automatizadas locales:** 5/5 reparaciones, escritorio y móvil sin desplazamiento horizontal, audio secuencial sin superposición, paso al taller con y sin movimiento reducido, sin errores de JavaScript.

**Límite visual reconocido:** todavía se usan personajes ilustrados SVG; no es una animación tridimensional ni un doblaje con sincronización labial fonética profesional.
