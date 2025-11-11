# web_project_homeland (proyecto 6)

Proyecto web para **Homeland** – Una celebración de las raíces culturales y orígenes geográficos del equipo.

## 🚀 Ver el proyecto en vivo

Puedes visitar el sitio desplegado en el siguiente enlace:  
[https://codebyroberto.github.io/web_project_homeland/](https://codebyroberto.github.io/web_project_homeland/)

## 📌 Descripción

Este sitio, titulado **“De patria a patria”**, narra un viaje simbólico desde Kentucky hasta Burundi, pasando por Gales y Ucrania, para destacar la diversidad global de un equipo profesional.

A través de tipografía cuidadosa, imágenes evocadoras y un diseño minimalista, se rinde homenaje a las historias personales que conectan a las personas con sus ciudades natales.

> “Todo ser humano es un artista, un ser de la libertad, llamado a participar en la transformación y reforma de las condiciones, el pensamiento y las estructuras que conforman e influyen en nuestras vidas.”  
> — Joseph Beuys

## 🛠 Tecnologías utilizadas

- **HTML5** – Estructura semántica (`<header>`, `<main>`, `<section>`, `<footer>`)
- **CSS3** – Estilos modulares con metodología **BEM (Flat)**
- **CSS Grid** – Usado en `photo-grid` y `places` (requisito crítico del Sprint 6)
- **Flexbox** – Para alineación interna de componentes
- **normalize.css** – Para consistencia entre navegadores
- **Fuentes locales** – Familia **Inter** cargada en formato `.woff2`
- **Responsive Design** – Compatible con desktop (1280px), tablet (768px) y mobile (320px)
- **Git** – Control de versiones con GitHub Desktop
- **Archivos de configuración** – `.editorconfig`, `.prettierignore`, `.gitignore`

## 📏 Breakpoints

El diseño está optimizado para tres tamaños de pantalla:

| Dispositivo | Ancho máximo | Características                            |
| :---------- | :----------- | :----------------------------------------- |
| Desktop     | 1280px       | Diseño completo, alineación precisa        |
| Tablet      | 768px        | Tipografía y espaciado ajustados           |
| Mobile      | 320px        | Contenido apilado, legibilidad prioritaria |

## ✨ Características clave del Sprint 6

- ✅ **Sección `photo-grid`** con 8 imágenes en **CSS Grid (4 columnas en desktop)**
- ✅ **Sección `places`** con tarjetas interactivas (ciudad, descripción, botón “Compra esta obra como NFT”)
- ✅ **Botones estilizados** con estados `:hover` para accesibilidad
- ✅ **Imágenes responsivas** con `object-fit: cover` y `alt` en español
- ✅ **Sin altura fija** en elementos de texto (usa `line-height` en lugar de `height`)
- ✅ **No se usa `!important`**
- ✅ **Validación W3C** – HTML semántico, sin `<b>`, `<i>`, ni `<br>` innecesarios
- ✅ **Metaetiquetas SEO completas** (`lang="es"`, `description`, `author`, `viewport`)

## 🗂 Estructura del proyecto

web_project_homeland/
├── .editorconfig
├── .gitignore
├── .prettierignore
├── favicon.ico
├── index.html
├── pages/
│ └── index.css # @import normalize → fonts → bloques
├── blocks/
│ ├── page.css
│ ├── header.css
│ ├── gallery.css
│ ├── photo-grid.css # NUEVO – Grid de 8 imágenes
│ ├── places.css # NUEVO – Tarjetas con botón NFT
│ └── footer.css
├── images/
│ ├── hero-image.jpg
│ ├── \_image (1).png
│ ├── \_image (2).png
│ ├── \_item_gales_g.png
│ ├── \_item_atardercer.png
│ ├── \_item_campo.png
│ ├── \_item_ciudadio.png
│ ├── \_item_playa.png
│ ├── \_item_zonaverde.png
│ └── logo.svg
├── vendor/
│ ├── normalize.css
│ ├── fonts.css # @font-face + family Inter
│ └── fonts/ # Archivos .woff2 de Inter
└── README.md

## 🚀 Cómo ejecutar el proyecto

1. Clona o descarga este repositorio.
2. Abre `index.html` en tu navegador (recomendado: Chrome o Firefox).
3. ¡Listo! No se requiere servidor, pero si usas **Live Server (VS Code)**, verás los cambios en tiempo real.

## 📝 Autor

**Roberto Eduardo de la Rosa Antunez**  
Front-end Developer  
[GitHub](https://github.com/codebyroberto)
