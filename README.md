# Mechanical Design Department — sitio web

Sitio estático de una página (HTML + CSS + JS, sin dependencias) para https://mechanicaldesigndept.com

- `index.html` — sitio completo (SEO, datos estructurados JSON-LD, Open Graph)
- `robots.txt`, `sitemap.xml` — indexación
- `vercel.json` — headers de seguridad y caché

Deploy: Vercel (preset "Other", sin comando de build, directorio raíz `/`). Cada push a `main` publica automáticamente.
