# Escondite abisal

Un pequeño pulpo violeta y su truco de tinta. Animación pixel art autónoma creada con la skill `pixel-anims`: Canvas 2D, paleta de 32 colores, resolución lógica de 160 × 90, escalado entero y simulación fija a 60 Hz. Sin dependencias, imágenes externas ni peticiones de red.

## Ver la animación

Descarga y abre **[pulpo-tinta.html](pulpo-tinta.html)** en un navegador moderno. No requiere instalación ni servidor. La **[vista previa GIF](pulpo-tinta-preview.gif)** muestra el bucle; los controles están en el HTML.

- **Pausar / Reanudar** o **Espacio**: detener y continuar.
- **Reiniciar** o **R**: volver al inicio, conservando el estado de pausa.
- Si el sistema solicita reducir movimiento, comienza en pausa; pulsa Reanudar para reproducirla.

| Tiempo | Acción |
| --- | --- |
| 0–2 s | Flotación, tentáculos y parpadeo |
| 2–3 s | Susto y contracción |
| 3–5 s | Expansión de tinta con remolinos y partículas |
| 5–6 s | Disipación; solo quedan burbujas |
| 6–8 s | Nube pequeña y reaparición a la derecha |
| 8–10 s | Sonrisa, baile y vuelta al inicio |

## Validación

Motor ENGINE de la skill conservado sin cambios. Comprobadas capturas en los ticks 0, 150, 180, 186, 192, 240, 330, 390, 432, 510 y 600. El fotograma completo del tick 600 coincide píxel a píxel con el del tick 0. Verificados los controles, el teclado, la preferencia de movimiento reducido y cuatro tamaños de pantalla en Chromium, sin errores JavaScript.

La ocultación prolongada del personaje por la tinta es intencionada y responde a la secuencia solicitada; es la excepción a la recomendación de la skill de mantener visible la silueta durante los efectos.

## Publicar en GitHub Pages

En los ajustes de este repositorio, abre **Pages** y selecciona **Deploy from a branch → main → / (root)**. Guarda la selección. La entrada `index.html` abre la animación automáticamente y `.nojekyll` permite servir los archivos directamente.

La dirección prevista, una vez completado el despliegue, es `https://nuriadom91-dev.github.io/MAR/`.
