# ExtremeBike: qué revisar antes de publicar

Todo se edita en `index.html`. Busca la palabra **EDITAR** (Ctrl+F) para encontrar cada punto.

## Obligatorio
1. ~~Dirección~~ ✅ Calle Segunda 599, Placilla (ya cargada).
2. **Precios:** los 8 servicios tienen precios **de ejemplo** ("desde $25.000", etc.). Cámbialos por los reales, o pon "Consultar".
3. ~~Reseñas~~ ✅ 3 reseñas reales de Google (ya cargadas).
4. ~~Preguntas frecuentes~~ ✅ 48–72 h, tarjeta/efectivo/transferencia, retiro en Placilla y Curauma (ya cargadas). Si cambias una respuesta, cámbiala también en el bloque `FAQPage` del `<head>`.
   - Pendiente: los tiempos de los demás servicios ("En el día", "24 h", "3–5 días"…) son de ejemplo, igual que los precios.

## Recomendado
- Crea o verifica la ficha de **Google Business Profile** de la tienda y pide reseñas a clientes.
- Después de publicar, envía `https://extremebike.cl/sitemap.xml` en Google Search Console.
- Si cambias `styles.css` o `main.js`, actualiza el número `?v=20261020` en `index.html` para que los visitantes vean la versión nueva.

## Publicar
Sube **todo el contenido** de esta carpeta (incluido `.htaccess`, que es un archivo oculto) a `public_html` en tu hosting.
El `.htaccess` redirige las direcciones antiguas (/services, /products, /about) a su sección nueva, para no perder posicionamiento en Google.
