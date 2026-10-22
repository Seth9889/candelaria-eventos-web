# Candelaria Eventos — sitio público

Catálogo responsive con búsqueda, filtros, carrito de consulta y armado de mensaje para WhatsApp.

## Publicar con GitHub Pages
1. Abrí **Settings** del repositorio.
2. Entrá a **Pages**.
3. En **Build and deployment**, seleccioná **Deploy from a branch**.
4. Elegí rama `main` y carpeta `/(root)`; guardá y esperá el despliegue.
5. URL esperada: https://seth9889.github.io/candelaria-eventos-web/

## Importante antes de publicar
El catálogo en `app.js` contiene categorías de ejemplo y precios pendientes; no son precios comerciales confirmados. Reemplazá los elementos de `catalog` con productos, descripciones, precios e imágenes reales. Actualmente los precios figuran como “Consultar”.

WhatsApp está configurado para el número comercial internacional 542302416671. El sitio abre un mensaje preparado; el cliente debe revisarlo y enviarlo. No lo manda automáticamente.

Este repositorio público solo debe contener archivos de la web. Nunca agregues contraseñas, tokens ni claves privadas. GitHub Pages es estático y no ejecuta un backend. Para administrar productos de forma segura hará falta conectar este sitio al backend privado mediante endpoints autenticados.
