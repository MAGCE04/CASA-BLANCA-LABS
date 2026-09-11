# Casa Blanca Labs — Landing Page

Página web de **Casa Blanca Labs** — Web3 community infrastructure & growth. La agencia de GTM para LATAM.

## Estructura

- `index.html` — página completa, sin dependencias ni build. HTML + CSS + JS en un solo archivo.
- Logo recreado como SVG vectorial inline (nítido en cualquier tamaño, hereda el color con `currentColor`).
- Tipografías vía Google Fonts: Space Grotesk (display), Manrope (texto), Michroma (wordmark).

## Ver en local

Basta con abrir `index.html` en el navegador, o:

```bash
npx serve .
```

## Deploy

**Producción:** https://casablancalabs.higgsfield.app (Cloudflare Worker vía Higgsfield; el video de intro `intro.mp4` vive en ese deploy).

Al ser un sitio estático de un solo archivo, también funciona directo en GitHub Pages, Vercel, Netlify o Cloudflare Pages sin configuración.

## Pendiente

- Reemplazar el email de contacto (`mailto:` en la sección de contacto) por el real.
- Añadir enlaces a redes (X, Telegram, Discord) en el footer cuando estén definidos.
