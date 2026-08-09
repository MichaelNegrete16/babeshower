# Baby Shower de Isaac David

Invitación digital. Una sola página, sin dependencias ni build.

**5 de septiembre · 7:00 PM · Escalón Villa, por la tienda donde Efrén**

## Cómo funciona

1. **El sobre** — se abre con un toque y da paso a la tarjeta
2. **La invitación** — bienvenida, el nombre y los papás
3. **Confirmación** — el invitado busca su nombre en la lista; quien no esté, no pasa
4. **Los detalles** — fecha, hora y lugar aparecen solo después de confirmar
5. **Cuenta regresiva** — corre en vivo hasta el día del evento

## Editar

Todo vive en `index.html`. La configuración está al principio del `<script>`:

- `WHATSAPP` — número al que llegan las confirmaciones
- `FECHA` — fecha y hora del evento
- `INVITADOS` — la lista. Un nombre por línea; agrega `| 4` para dar 4 cupos
- `CUPOS_POR_DEFECTO` — cupos de quien no tenga número propio

La búsqueda ignora tildes y mayúsculas: `adrian` encuentra a `Adrián`.

## Publicar

Está en GitHub Pages. Cada push a `main` actualiza el sitio.
