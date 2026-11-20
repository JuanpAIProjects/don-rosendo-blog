# La libreta de Don Rosendo — blog de Grupo Santa Rosa

Blog estático de **Don Rosendo**, la mascota de Grupo Santa Rosa: tips, checklists y datos reales para eventos y hospedaje en Cholula y Puebla. Sin paso de build; Netlify sirve los archivos tal cual desde la raíz.

## Estructura
- `index.html` — portada (autor Don Rosendo, tarjetas de artículos, las diez maneras de celebrar, CTA de WhatsApp).
- `posts/` — un HTML por artículo. El primero: `2026-11-20-presentacion-don-rosendo.html`.
- `plantilla-post.html` — plantilla con marcadores `{{...}}` para los artículos nuevos.
- `posts.json` — índice de artículos (fecha, título, resumen, url, tema, lectura, video).
- `assets/img/` — imágenes (personaje, logo de Grupo Santa Rosa, fotos de referencia).
- `assets/video/` — videos enlazados desde los artículos; también es el host público de video para Buffer cuando el sitio esté en vivo.
- `netlify.toml` — publicación sin build y cabeceras.

## Cómo se publica un artículo nuevo
1. Copiar `plantilla-post.html` a `posts/AAAA-MM-DD-slug.html` y reemplazar los marcadores.
2. Agregar la entrada a `posts.json` (arriba) y la tarjeta a `index.html`.
3. Empujar los archivos de TEXTO con el procedimiento snapshot del conector de GitHub (`github push-files`). Los BINARIOS (imágenes y video) se suben por la web de GitHub: el push de texto los rechaza.
4. Netlify despliega solo al detectar el push (sitio enlazado al repo).

## Reglas de la casa
- Voz de Don Rosendo: elegante, pícara y servicial. Español de México.
- Nada de precios exactos ni promesas de disponibilidad: la cotización la cierra ventas de Grupo Santa Rosa (WhatsApp +52 222 616 8681).
- Capacidad siempre por espacio; el 1,500 es solo el Complejo Zerezotla completo.
- Identidad digital oficial de GSR (la del cotizador de GSR360): fondo #1F1C3B, paneles #2D2D49, rosa #F8B5CE, verde WhatsApp #247A40, texto blanco. PROHIBIDO vino/burgoña y dorado (eso era de gráficos impresos). Titulares en Fraunces.
- Contenido: la base son las 10 maneras del cotizador (Ardizana, Arcadia, Zerezotla, Cerezos, Terraza Capulines, Magdalena, Complejo Zerezotla, Terraza Hotel Santa Rosa, Hotel Santa Rosa y eventos a domicilio) y los tipos de evento son amplios: bodas, XV años, graduaciones, bautizos, corporativos y posadas — nada de reducir GSR a «bodas y fiesta».
- Visuales: solo gráficos planos de fábrica con la mascota oficial; las fotos reales viven solo en las cuentas oficiales de GSR.
