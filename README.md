# Fiore · La carta

Landing de Viandas Fiore (Adrogué): carta de viandas congeladas con pedido directo por WhatsApp.

## Publicar en GitHub Pages
1. Subí este repositorio a GitHub (index.html y la carpeta assets en la raíz).
2. Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.
3. En un par de minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Editar platos, precios y datos
Todo está al final de `index.html`, en el bloque `EDITAR ACÁ`:
- `CONFIG.whatsapp`: número sin + ni espacios.
- `CONFIG.zonas` y `CONFIG.faq`: completar lo que está entre corchetes.
- `ITEMS`: nombre, descripción, precio y foto de cada plato. Si un plato no tiene foto, dejá `img:""` y se muestra una tarjeta tipográfica.

Las fotos van en `assets/img/`. Para la vista previa al compartir el link (WhatsApp, Instagram), cambiá `og:image` por la URL completa de la foto una vez publicado.
