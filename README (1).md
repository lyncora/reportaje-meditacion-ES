# Audio Reportaje — Apaga tu Ansiedad

Mini página estática para reproducir el audio MP3 del programa.

## Archivos

- `index.html` — página del reproductor.
- `audio-reportaje.mp3` — coloca aquí tu archivo MP3 y conserva exactamente este nombre.

## Cómo usarlo

1. Descarga tu MP3 desde Google Drive.
2. Renómbralo exactamente:
   `audio-reportaje.mp3`
3. Coloca el MP3 en la misma carpeta que `index.html`.
4. Sube ambos archivos a GitHub.
5. Conecta el repositorio a Vercel y despliega como proyecto estático.

No necesita base de datos, servidor ni código backend.

## Importante

Esta página está pensada para servir el audio mediante Vercel. El MP3 se sirve como un archivo estático del mismo dominio, por lo que el reproductor HTML5 puede reproducirlo directamente.

Si el MP3 es muy grande, conviene usar almacenamiento/CDN para archivos grandes en lugar de incluirlo directamente en Git.
