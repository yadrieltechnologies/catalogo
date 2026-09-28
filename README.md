# Catálogo - Yadriel Technology

Sitio estático del catálogo. Listo para Netlify + Google Search Console.

## Archivos
- `index.html` - tienda principal
- `google0c51c3eb86966136.html` - verificación de Google (NO borrar, debe quedar en la raíz)
- `robots.txt` - permite todo + sitemap
- `sitemap.xml` - cambia `https://TU-SITIO.netlify.app` por tu URL real de Netlify
- `netlify.toml` - publish = "." para servir desde la raíz

## Deploy en Netlify
1. Netlify -> Add new site -> Import from GitHub -> `yadrieltechnologies/catalogo`
2. Build command: vacío, Publish directory: `.` (o `.` ya configurado en netlify.toml)
3. Deploy, luego verifica que abre: `https://TU-SITIO.netlify.app/google0c51c3eb86966136.html`
4. En Google Search Console dale a Verificar.

## Después del deploy
1. Reemplaza `TU-SITIO.netlify.app` en `sitemap.xml` y `robots.txt` por tu dominio real.
2. Re-subir y en Search Console -> Sitemaps -> agregar `/sitemap.xml`.
