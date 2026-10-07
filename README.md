# CREDKA S. F. - App Instalable (PWA)

Esta es la versión **instalable** de CREDKA S. F. como Progressive Web App (PWA).

## Cómo instalarla en el celular

### Android (Chrome / Edge / Samsung Internet)
1. Subí todos los archivos a un hosting (o usá un servidor local).
2. Abrí la página en el navegador.
3. Tocá el menú **⋮** → **"Agregar a la pantalla de inicio"** o **"Instalar aplicación"**.
4. Confirmá. La app quedará como una app nativa.

### iPhone / iPad (Safari)
1. Abrí la página en Safari.
2. Tocá el botón **Compartir** (□↑).
3. Elegí **"Agregar a la pantalla de inicio"**.
4. Confirmá.

## Archivos incluidos
- `index.html` → La aplicación completa
- `manifest.json` → Configuración de la PWA
- `sw.js` → Service Worker (funciona offline)
- `icon-192.png` y `icon-512.png` → Íconos de la app

## Notas importantes
- Para que la instalación funcione, la app **debe servir desde HTTPS** (o localhost).
- Los datos se guardan en el celular (localStorage).
- Funciona offline después de la primera carga.

## Opciones para publicar gratis
- **Netlify Drop** (arrastrá la carpeta)
- **GitHub Pages**
- **Vercel**
- **Cloudflare Pages**
