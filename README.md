# 🌿 Nebularspell — Sitio Web Responsivo con Bootstrap

Proyecto personal construido con **Bootstrap 5** cuyo objetivo es practicar, aprender y reforzar tecnologías web. La temática se centra en comida saludable con una estética minimalista.

## ✨ Características

- 📱 **Diseño responsivo** — Se adapta a móvil, tablet y escritorio.
- 🎯 **Bootstrap 5** — Sistema de grillas, utilidades y componentes.
- 🧩 **Componentes** — Navbar con buscador, carrusel, cards de producto, newsletter, footer.
- ♿ **Accesibilidad básica** — HTML semántico, `skip link`, `aria-label` en iconos, foco visible.
- 🔎 **SEO básico** — Meta description, Open Graph y Twitter Card.
- 🎨 **Paleta propia** — Verdes/tierra con variables CSS que sobrescriben Bootstrap.

## 🛠️ Tecnologías

- HTML5
- CSS3 (variables y `@media` queries)
- Bootstrap 5 + Bootstrap Icons (vía CDN con SRI)
- Tipografía **Poppins** (Google Fonts)

## 🚀 Cómo verlo

```bash
git clone https://github.com/BinaryBeginner/sitio-bootstrap.git
cd sitio-bootstrap
```

Opción 1 — abrir directamente en el navegador:

```bash
xdg-open index.html      # Linux
open index.html          # macOS
start index.html         # Windows
```

Opción 2 — servidor local estático (recomendado):

```bash
npm start                # levanta http-server en http://localhost:8080
```

> Las dependencias se cargan desde CDN; `npm install` es opcional y sólo es útil para trabajar offline.

## 📁 Estructura

```
.
├── assets/             # imágenes (webp)
├── css/
│   └── style.css       # estilos propios + overrides de Bootstrap
├── index.html
├── package.json
└── README.md
```

## 📄 Estado

⏳ **En progreso** — se seguirán añadiendo secciones (detalle de producto, carrito, recetas).
