# video-player
Como particularidades:
En el CSS usaremos calc

Referenciaremos los elementos del DOM preferiblemente con querySelector (por clases o por elemento), en lugar de hacerlo con getElementById

Para representar la barra que muestra por donde va el vídeo (progressBar) haremos `${(e.offsetX / progressRange.offsetWidth)*100}%`

e.offset devuelve en qué punto hemos hecho clic

elemento.offsetWidth devuelve la anchura del elemento. En particular, progressRange.offsetWidth devuelve la anchura de la barra (completa) de duración del vídeo.

# Recursos
[Video DOM Reference](https://www.w3schools.com/tags/ref_av_dom.asp)

[How to Fullscreen](https://www.w3schools.com/howto/howto_js_fullscreen.asp)

Fontawesome para los iconos de play, volume y fullscreen