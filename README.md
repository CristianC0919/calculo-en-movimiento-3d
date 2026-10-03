# Cálculo en Movimiento 3D — función configurable

Esta versión está preparada para que el usuario escriba **la función matemática que le asigne la docente**.

## Funciones automáticas

El programa usa Math.js para:
- interpretar la función escrita;
- calcular automáticamente f'(x);
- calcular automáticamente f''(x);
- evaluar f(a) y f'(a);
- construir la recta tangente;
- buscar numéricamente puntos críticos;
- representar f, f' y f'' en la escena 3D.

### Ejemplos aceptados

```text
x^2
x^3 - 2*x
sin(x)
cos(x)
exp(x)
sqrt(x)
1/x
x^4 - 4*x^2
```

También se pueden usar expresiones combinadas compatibles con Math.js.

## Las cinco interacciones

1. **1 dedo:** cambia x=a y muestra f(a) y f'(a).
2. **2 dedos:** construye la recta tangente en x=a.
3. **3 dedos:** muestra f(x), f'(x) y f''(x).
4. **4 dedos:** busca y muestra puntos críticos dentro del rango seleccionado.
5. **5 dedos:** ejecuta un reto de razón de cambio usando la función introducida.

## Controles alternativos

- Teclas `1` a `5`: cambiar interacción.
- Flecha izquierda/derecha: mover x.
- `R`: reiniciar.
- Mouse: arrastrar horizontalmente sobre la gráfica.

## GitHub Pages

1. Crea un repositorio.
2. Sube `index.html`, `style.css`, `app.js` y `README.md`.
3. Ve a Settings → Pages.
4. Selecciona `Deploy from a branch`.
5. Rama `main`, carpeta `/root`.
6. Guarda y abre el enlace generado.
7. Pulsa **Activar cámara** y acepta el permiso.

La cámara necesita HTTPS; GitHub Pages proporciona HTTPS.

## Nota matemática

La búsqueda de puntos críticos es numérica y depende del rango de la gráfica. Para funciones con discontinuidades, dominios restringidos o comportamientos especiales, el resultado debe verificarse matemáticamente antes de la sustentación.

## Tecnologías

HTML5, CSS3, JavaScript, Three.js, Math.js, MediaPipe Hands y GitHub Pages.
