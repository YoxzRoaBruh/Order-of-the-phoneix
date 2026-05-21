#  Order of the Phoenix

Sitio web del clan **Order of the Phoenix** para *Among Us*.  
Incluye pantalla de carga animada, intro con GIF y efectos visuales.

## Vista previa

- **Carga**: Logo del fénix con llamas animadas y barra de progreso (2.5s)
- **Intro**: GIF a pantalla completa con sonido ambiental y efecto de puñalada sincronizado
- **Contenido**: Secciones informativas, galería de dinámicas, carrusel de fundadores/staff, modal para imágenes

## Uso local

Abrir `index.html` en el navegador (recomendado usar un servidor local para evitar restricciones `file://`):

```bash
# Con Python
python -m http.server 8000
# Con Node
npx serve .
```

## Archivos

| Archivo | Descripción |
|---------|-------------|
| `index.html` | Página principal |
| `style.css` | Estilos y animaciones |
| `script.js` | Lógica de carga, intro, carrusel, modal y efectos |
| `intro.gif` | GIF de intro (desktop) |
| `movil.gif` | GIF de intro (móvil) |

## Personalización

- **Duración del GIF**: Editar `INTRO_DURATION` en `script.js` (en milisegundos)
- **Tiempo del stab**: Cambiar el factor `0.4` en `startIntro()` (40% de la duración)
- **Colores**: Variables CSS en `:root` al inicio de `style.css`

## Construido con

- HTML / CSS / JavaScript vanilla
- [Font Awesome](https://fontawesome.com) para iconos
- [Google Fonts](https://fonts.google.com) (Cinzel + Montserrat)
