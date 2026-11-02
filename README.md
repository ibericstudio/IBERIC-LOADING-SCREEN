IBERIC PROJECT LOADING SCREEN v2.1
==================================

INSTALACION
1. Extrae la carpeta iberic_loading en resources.
2. En server.cfg coloca:
       ensure iberic_loading
3. No cambies el nombre de la carpeta si usas la ruta anterior.

CORRECCIONES
- Logo: se usa el PNG real incluido (iberic-project-logo.png).
- Musica: el MP4 original se conserva como music.mp4 y se extrae su pista a
  music.mp3, que es el formato de audio recomendado para CEF/FiveM.
- El reproductor tiene play/pausa y volumen 0-100%.
- Se intenta autoplay; si CEF lo bloquea, el usuario puede pulsar Play.
- El progreso escucha el evento loadProgress de FiveM y tiene un progreso
  visual de respaldo mientras no llega el evento nativo.

PERSONALIZACION
Edita html/config.js:
- logo: ruta del logo.
- musicUrl: ruta de la musica (por defecto assets/music.mp3).
- musicVolume: volumen inicial entre 0.0 y 1.0.
- accent / accentSecondary: colores.
- serverName / subtitle: nombre del servidor.

IMPORTANTE
Si sustituyes la musica, puedes poner otro MP3 en html/assets y cambiar musicUrl.
Si quieres usar otro MP4, coloca el archivo en html/assets y convierte su pista
a MP3 para máxima compatibilidad con FiveM CEF. El MP4 original enviado queda
incluido en este ZIP.
