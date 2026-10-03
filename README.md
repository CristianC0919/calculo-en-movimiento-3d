# Cálculo en Movimiento — Entrega 3

Aplicación web interactiva para Cálculo Diferencial con estética **negro, rojo y blanco**, gráfica 3D, cálculo simbólico de derivadas y reconocimiento de gestos con cámara.

## Incluye
- Funciones introducidas por el usuario con Math.js.
- Primera y segunda derivada calculadas automáticamente.
- Gráfica 3D con Three.js.
- Cámara y reconocimiento de 1 a 5 dedos con MediaPipe Hands.
- Cinco interacciones de la guía: evaluación, tangente, derivadas, críticos y razón de cambio.
- Controles alternativos por teclado y mouse.

## Publicar en GitHub Pages
1. Sube `index.html`, `style.css`, `app.js` y `README.md` a un repositorio.
2. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
3. Abre el enlace `https://TU-USUARIO.github.io/NOMBRE-REPOSITORIO/`.
4. Pulsa **ACTIVAR CÁMARA** y concede permiso.

La cámara requiere HTTPS; GitHub Pages cumple este requisito.

## Nota matemática
La búsqueda de puntos críticos es numérica. Para funciones con discontinuidades, restricciones de dominio o comportamientos especiales, los resultados deben verificarse manualmente.
