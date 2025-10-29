# web_project_homeland

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

- **HTML5** – Estructura semántica
- **CSS3** – Estilos modulares con metodología **BEM** y `@import`
- **normalize.css** – Para asegurar consistencia de estilos entre navegadores
- **Fuentes locales** – Inter Variable (cargada localmente para mejor rendimiento)
- **Responsive Design** – Compatible con desktop (1280px), tablet (768px) y mobile (320px)
- **Sin frameworks** – Código 100% vanilla

## 📏 Breakpoints

El diseño está optimizado para tres tamaños de pantalla:

| Dispositivo | Ancho máximo | Características                            |
| :---------- | :----------- | :----------------------------------------- |
| Desktop     | 1280px       | Diseño completo, alineación precisa        |
| Tablet      | 768px        | Tipografía y espaciado ajustados           |
| Mobile      | 320px        | Contenido apilado, legibilidad prioritaria |

## 🚀 Cómo ejecutar el proyecto

1.  Clona o descarga este repositorio.
2.  Abre `index.html` (el archivo en la raíz del proyecto) en tu navegador.
3.  ¡Listo! No se requiere servidor, pero si usas uno local (como Live Server en VS Code), tendrás una mejor experiencia.

## ✨ Buenas prácticas aplicadas

- ✅ **BEM** para clases CSS (evita conflictos y mejora mantenibilidad)
- ✅ **`normalize.css`** para un reseteo de estilos base consistente.
- ✅ **Fuentes locales** (mejor rendimiento y privacidad)
- ✅ **Valores relativos** (`%`, `fr`) en el layout de Grid.
- ✅ **`line-height` en decimales** (ej. `1.5`) para escalabilidad
- ✅ **`object-fit: cover`** para imágenes responsivas
- ✅ **Metaetiquetas SEO** y accesibilidad (`alt`, `lang`, `description`)

## 🗂 Estructura del proyecto

web_project_homeland/
├── index.html # Archivo HTML principal
├── pages/
│ └── index.css # Archivo CSS principal (importa todos los bloques)
├── blocks/ # Componentes CSS modulares
│ ├── page.css
│ ├── header.css
│ ├── gallery.css # Estilos del contenido principal
│ └── footer.css
├── images/
│ ├── hero-image.jpg
│ ├── logo.svg
│ └── favicon.png # Favicon del proyecto
├── Inter-4.1/ # Fuente Inter Variable
│ └── InterVariable.ttf
├── vendor/ # CSS de terceros
│ └── normalize.css
└── README.md

## ✨ Características clave

- ✅ Diseño responsivo en tres breakpoints (1280px, 768px, 320px)
- ✅ Metodología **BEM** para clases CSS
- ✅ Uso de **`normalize.css`**
- ✅ Fuentes descargadas y enlazadas localmente
- ✅ Imágenes optimizadas con `object-fit: cover`
- ✅ `line-height` en valores decimales (ej. `1.5`)
- ✅ Metaetiquetas SEO y accesibilidad básica

## 📝 Autor

**Roberto Eduardo de la Rosa Antunez**
Front-end Developer
[GitHub](https://github.com/codebyroberto)
