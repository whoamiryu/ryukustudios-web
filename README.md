# Ryuku Studios — Coming Soon

Landing page de "en construcción" para Ryuku Studios.

## Estructura

```
index.html          → la página (todo el CSS y JS va dentro de este archivo)
assets/logo.png      → tu logo, con el fondo negro quitado (fondo transparente)
assets/favicon.png   → tu logo original, usado como icono de pestaña
```

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `ryuku-studios` o `ryukustudios.github.io` si quieres usarlo como página principal de tu organización).
2. Sube estos tres elementos a la raíz del repositorio: `index.html`, la carpeta `assets/` completa, y `README.md` (opcional).
3. Ve a **Settings → Pages** en el repositorio.
4. En "Source", selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
5. Guarda. GitHub te dará una URL parecida a `https://tu-usuario.github.io/ryuku-studios/` — puede tardar 1-2 minutos en activarse.

Si usas dominio propio, añade un archivo `CNAME` con tu dominio, o configúralo desde la misma pantalla de Settings → Pages.

## Cosas para personalizar antes de publicar

- **Email de contacto**: busca `hola@ryukustudios.com` en `index.html` y cámbialo por tu correo real.
- **Copyright del footer**: dice "© 2026 Ryuku Studios" — actualízalo si cambia el año.
- **Texto**: el subtítulo bajo "Coming Soon..." es un placeholder editorial; cámbialo cuando quieras contar algo más concreto del juego.

## Notas técnicas

- Una sola página, sin dependencias de build ni frameworks — solo HTML/CSS/JS, así que funciona tal cual en GitHub Pages.
- Tipografías (Cormorant + Inter) se cargan desde Google Fonts vía CDN.
- Totalmente responsive (móvil/tablet/desktop) y respeta `prefers-reduced-motion`.
- El sello circular animado es puramente decorativo (SVG), no requiere ninguna librería.
