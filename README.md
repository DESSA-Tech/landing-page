# DESSA Tech — Landing Page

Landing page estática para DESSA Tech, plataforma integral de salud mental.

## Estructura

```
index.html          # Página principal
assets/
  fonts/            # Urbanist (TTF, todos los pesos)
  logo.svg
  logo-invertido.svg
  isotipo.svg
  isotipo-invertido.svg
vercel.json         # Config para deploy en Vercel
.nojekyll           # Deshabilita Jekyll en GitHub Pages
```

## Dev local

```bash
npx serve .
```

## Deploy en GitHub Pages

1. Hacer push a `main`:
   ```bash
   git add .
   git commit -m "deploy"
   git push origin main
   ```
2. Ir a **Settings → Pages** en el repositorio
3. En **Source**, seleccionar `Deploy from a branch`
4. Branch: `main`, carpeta: `/ (root)` → **Save**
5. El sitio queda en: `https://dessa-tech.github.io/landing-page/`

## Deploy en Vercel

Conectar el repositorio en [vercel.com](https://vercel.com). El `vercel.json` ya incluye headers de seguridad y clean URLs.

## Stack

- HTML5 estático
- [Tailwind CSS CDN](https://cdn.tailwindcss.com)
- [Material Symbols Outlined](https://fonts.google.com/icons)
- Fuente local: **Urbanist**
