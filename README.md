# <img src="https://img.icons8.com/fluency/48/null/technology.png" width="36" style="vertical-align:middle" alt="Nexus Tech"> Nexus Tech – La Transformación Digital

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/estado-activo-brightgreen?style=flat-square">
    <img alt="Estado: Activo" src="https://img.shields.io/badge/estado-activo-brightgreen?style=flat-square">
  </picture>
  <picture>
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  </picture>
  <picture>
    <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  </picture>
  <picture>
    <img alt="Git Flow" src="https://img.shields.io/badge/Git%20Flow-F05032?style=flat-square&logo=git&logoColor=white">
  </picture>
  <picture>
    <img alt="Licencia MIT" src="https://img.shields.io/badge/licencia-MIT-blue?style=flat-square">
  </picture>
</p>

<p align="center">
  <b>Revista digital de tecnología y gaming</b><br>
  Análisis profundos, reseñas honestas y una comunidad apasionada por la tecnología.<br>
  Proyecto académico de maquetación web con HTML5 y CSS3 puros.
</p>

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/overview-pages-1.png" width="28" style="vertical-align:middle"> Vista General

### Contexto

Este proyecto fue desarrollado como parte de la asignatura **Skill HTML + CSS** del programa de formación. El desafío planteado por el profesor consistía en construir un sitio web completo, funcional y visualmente profesional utilizando **exclusivamente HTML5 y CSS3**, sin frameworks, librerías externas ni JavaScript.

### Problema

Los estudiantes debían demostrar dominio de:

- Maquetación semántica con HTML5
- Sistema de diseño modular con CSS3
- Layouts complejos con **CSS Grid** y **Flexbox**
- **Diseño responsive** con enfoque **Mobile First**
- Metodología **BEM** para nomenclatura de clases
- Animaciones y transiciones CSS
- Variables CSS para tematización
- Control de versiones con **Git** y **Git Flow**
- Documentación profesional con **Conventional Commits**

### Solución

**Nexus Tech** es una revista tecnológica digital compuesta por **7 páginas web** que cubren un ecosistema completo de contenido: portada con artículos destacados, categorías con filtros, reseñas con tabla comparativa, foro comunitario, agenda de eventos, formulario de contacto y artículo individual. Todo construido con **código 100% nativo**, sin una sola línea de JavaScript, demostrando que CSS3 moderno es capaz de crear experiencias interactivas y atractivas por sí mismo.

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/goal.png" width="28" style="vertical-align:middle"> Objetivos del proyecto

| Objetivo | Descripción |
|----------|-------------|
| 🎯 **Maquetación semántica** | Utilizar etiquetas HTML5 significativas (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<nav>`, `<details>`, `<picture>`) |
| 🎯 **CSS modular** | Organizar el código en archivos separados por responsabilidad: diseño system, layout, componentes y responsive |
| 🎯 **Metodología BEM** | Aplicar Bloque\_\_Elemento--Modificador en todas las clases CSS |
| 🎯 **Mobile First** | Diseñar primero para móviles y escalar hacia arriba con media queries |
| 🎯 **Sin frameworks** | Demostrar que CSS3 puro es suficiente para proyectos profesionales |
| 🎯 **Sin JavaScript** | Lograr interactividad (menú hamburguesa, acordeones, animaciones) solo con CSS |
| 🎯 **Git profesional** | Usar Git Flow con Conventional Commits y ramas semánticas |
| 🎯 **Documentación** | README profesional que documente la arquitectura completa |

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/laptop-coding.png" width="28" style="vertical-align:middle"> Tecnologías utilizadas

<div align="center">

| Tecnología | Uso |
|:-----------|:----|
| <img src="https://img.icons8.com/color/48/null/html-5--v1.png" width="20"> **HTML5** | Estructura semántica de todas las páginas |
| <img src="https://img.icons8.com/color/48/null/css3.png" width="20"> **CSS3** | Estilos, animaciones, diseño responsive |
| <img src="https://img.icons8.com/fluency/48/null/grid.png" width="20"> **CSS Grid** | Layouts de artículos, reseñas, eventos, footer |
| <img src="https://img.icons8.com/fluency/48/null/parallel-tasks.png" width="20"> **Flexbox** | Header, hero, cards, meta-info, formularios |
| <img src="https://img.icons8.com/fluency/48/null/responsive.png" width="20"> **Media Queries** | 6 breakpoints para adaptación responsive |
| <img src="https://img.icons8.com/fluency/48/null/color-palette.png" width="20"> **CSS Variables** | Sistema de diseño centralizado en `:root` |
| 🧩 **BEM** | Nomenclatura consistente en todo el CSS |
| <img src="https://img.icons8.com/fluency/48/null/play--v1.png" width="20"> **CSS Animations** | Keyframes, transiciones y microinteracciones |
| <img src="https://img.icons8.com/color/48/null/git.png" width="20"> **Git + GitHub** | Control de versiones con Git Flow |
| 📝 **Conventional Commits** | Commits semánticos con emojis (:sparkles:, :lipstick:, :iphone:) |

</div>

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/architecture.png" width="28" style="vertical-align:middle"> Arquitectura del proyecto

```
Proyecto_Skill_HTML_CSS_NexusTech/
│
├── 📄 index.html                        # Página de inicio / landing principal
├── 📄 LÉAME.md                          # Documentación del proyecto
├── 📄 README.md                         # README profesional en español
├── 📄 .gitignore                        # Archivos ignorados por Git
│
├── 📁 activos/                          # Recursos estáticos
│   ├── 📁 css/                          # ❖ Hojas de estilo (4 módulos)
│   │   ├── main.css                     #   ─ Variables, reset, keyframes, utilidades
│   │   ├── layout.css                   #   ─ Estructura: header, hero, grids, footer
│   │   ├── componentes.css              #   ─ Componentes: cards, buttons, forms
│   │   └── responsive.css               #   ─ Media queries Mobile First
│   │
│   ├── 📁 img/                          # 🖼️ Imágenes del proyecto
│   │   ├── 📁 articulos/                #   15 imágenes de artículos (IA, gaming, etc.)
│   │   ├── 📁 reseñas/                  #   6 imágenes de productos reseñados
│   │   ├── 📁 hero/                     #   Hero banner principal
│   │   ├── 📁 eventos/                  #   Imagen de conferencia
│   │   ├── 📁 contacto/                 #   Captura de mapa
│   │   ├── 📁 comunidad/                #   (disponible para futuras imágenes)
│   │   ├── 📁 logos/                    #   (disponible para futuros logos)
│   │   └── 📁 ui/                       #   (disponible para futuros elementos UI)
│   │
│   ├── 📁 iconos/                       # 🏷️ (disponible para iconos SVG)
│   └── 📁 js/                           # ⚡ (disponible para futuros scripts)
│
├── 📁 páginas/                          # 📄 Páginas secundarias del sitio
│   ├── categorías.html                  #   Categorías con sidebar y filtros
│   ├── resenas.html                     #   Reseñas con tabla comparativa
│   ├── comunidad.html                   #   Foro, FAQ y comunidad
│   ├── eventos.html                     #   Calendario de eventos
│   ├── contacto.html                    #   Formulario de contacto
│   └── inteligencia-artificial.html     #   Artículo individual
│
└── 📁 articulos/                        # 📝 Artículos (carpeta de respaldo)
    └── inteligencia-artificial.html     #   Versión standalone del artículo
```

### Función de cada carpeta

| Carpeta | Propósito |
|---------|-----------|
| `activos/css/` | Contiene la **arquitectura CSS completa** dividida en 4 módulos con responsabilidades únicas y bien definidas |
| `activos/img/` | Almacena todos los **recursos gráficos** organizados por sección: artículos, reseñas, hero, eventos y contacto |
| `activos/iconos/` | Espacio reservado para **iconografía SVG** o font icons en futuras iteraciones |
| `activos/js/` | Preparado para **futuras funcionalidades JavaScript** (sin JS en la versión actual) |
| `páginas/` | Contiene las **6 páginas secundarias** que, junto con `index.html`, completan las 7 páginas del sitio |
| `articulos/` | Archivos de artículo en formato plano, utilizados como fuente de contenido para la página de artículo individual |

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/web.png" width="28" style="vertical-align:middle"> Páginas desarrolladas

### 🏠 Inicio (`index.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Landing page que presenta la marca y enlaza a todas las secciones |
| **Componentes** | Loader animado, barra de progreso, header sticky, hero cinematográfico, trending strip, story section, grid de artículos destacados, footer |
| **Estructura** | `header → hero → trending → story-section → articles-grid → footer` |
| **Diseño** | Hero con imagen de fondo a pantalla completa y overlay degradado oscuro. Artículos en grid responsivo (1→2→3 columnas) |
| **UX** | Animación de entrada secuencial (heroReveal), scroll indicator, hover en tarjetas con elevación y escalado de imagen, loader de pantalla de carga |

> 💡 **Detalle:** El hero utiliza un `<picture>` con `source` para cargar la imagen en alta resolución solo en desktop, optimizando el rendimiento en móviles.

---

### 🏷️ Categorías (`páginas/categorías.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Navegar artículos por categoría con filtros y búsqueda |
| **Componentes** | Sidebar con buscador interno, filtros por categoría (IA, Gaming, Ciberseguridad, etc.), filtro por fecha, 15 tarjetas de artículo, paginación (6 páginas) |
| **Estructura** | `sidebar (sticky) + article-grid + pagination` en layout de 2 columnas (260px + 1fr) en desktop |
| **Diseño** | Sidebar con fondo `--color-surface`, inputs con focus glow naranja, filtros activos con highlight |
| **UX** | Búsqueda en tiempo real visual, categorías con contador numérico, paginación con estado activo y hover |

> ⚠️ **Nota:** La búsqueda es visual (placeholder de funcionalidad); el filtrado dinámico requeriría JavaScript.

---

### ⭐ Reseñas (`páginas/resenas.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Exhibir reseñas de productos tecnológicos con ratings y comparativa |
| **Componentes** | 6 review cards con estrellas, tabla comparativa de especificaciones, sección de comentarios de la comunidad |
| **Estructura** | `review-grid → comparison-table → comments-section` |
| **Diseño** | Estrellas con color `--color-accent-secondary` (dorado). Tabla con bordes sutiles y hover en filas. Comentarios con avatares, acciones (me gusta, responder) |
| **UX** | Cards con hover elevación y zoom de imagen. Estrellas semánticas con soporte para medias estrellas |

> 🔍 **Detalle técnico:** Las medias estrellas se implementan con un pseudo-elemento `::after` con `width: 50%` y `overflow: hidden`, sin necesidad de sprites ni icon fonts.

---

### 💬 Comunidad (`páginas/comunidad.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Foro de discusión, preguntas frecuentes y badges de usuarios |
| **Componentes** | 4 posts de foro (con avatar, autor, fecha, votos, respuestas), sidebar con usuarios activos y temas populares (badges), sección FAQ con acordeones `<details>/<summary>` |
| **Estructura** | `post-list (flex) + sidebar → FAQ accordion` |
| **Diseño** | Posts con borde sutil que se ilumina en hover. Badges con fondo semitransparente. Acordeones nativos sin JavaScript |
| **UX** | FAQ completamente funcional con etiquetas `<details>` nativas de HTML5. Transiciones en hover de posts y badges |

> 🎯 **Técnica clave:** Los acordeones FAQ usan la etiqueta HTML5 nativa `<details>` + `<summary>`, con un pseudo-elemento `::after` que rota 45° al abrirse (`details[open]`), todo sin JavaScript.

---

### 🗓️ Eventos (`páginas/eventos.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Mostrar calendario de próximos eventos tecnológicos |
| **Componentes** | 5 event cards con fecha destacada, título, descripción, meta-info (ubicación, hora, ponente), CTA banner final |
| **Estructura** | `event-list → cta-banner` |
| **Diseño** | Cards con layout horizontal (flex) que cambia a vertical en móvil. Caja de fecha con día grande en naranja y mes en gris |
| **UX** | Hover con elevación y borde iluminado. Meta-información con iconos tipográficos. Banner CTA con botón a contacto |

---

### 📞 Contacto (`páginas/contacto.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Formulario de contacto e información de la empresa |
| **Componentes** | Formulario con 4 campos (nombre, email, asunto, mensaje), tarjetas de información (email, ubicación, horario), redes sociales, placeholder de mapa |
| **Estructura** | `form (2 columnas) + info-cards (sidebar)` |
| **Diseño** | Inputs con estilo oscuro, focus glow naranja, select personalizado con flecha SVG inline. Tarjetas con listado de definición `<dl>` |
| **UX** | Placeholders visibles, select semántico, botón de envío con estilo primary. Mapa interactivo como placeholder visual |

> 🎨 **Detalle:** El select personalizado usa una flecha SVG codificada inline en `background-image`, eliminando la necesidad de iconos externos.

---

### 📰 Artículo Individual (`páginas/inteligencia-artificial.html`)

| Aspecto | Descripción |
|---------|-------------|
| **Objetivo** | Página de artículo completo con lectura inmersiva |
| **Componentes** | Hero de artículo (categoría, fecha, autor), tabla de contenidos (TOC), cuerpo con secciones, blockquotes, bloques de código, grid de artículos relacionados |
| **Estructura** | `article-hero → TOC → article-body (5 secciones) → related-articles` |
| **Diseño** | Tipografía amplia, max-width de lectura (700px), blockquote con borde izquierdo naranja, código con fondo `--color-surface` |
| **UX** | TOC con anclas internas (`#id`), imágenes responsivas, breadcrumb visual de categoría, autor con avatar |

> 📐 **Detalle:** El ancho del contenido del artículo está limitado a 700px para optimizar la legibilidad, siguiendo la regla de los ~66 caracteres por línea.

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/design.png" width="28" style="vertical-align:middle"> Sistema de Diseño

### 🎨 Paleta de colores

```css
:root {
  /* Tonalidades oscuras (fondo y superficies) */
  --color-primary:          #0A0A0A;  /* Fondo principal */
  --color-secondary:        #111111;  /* Fondo secundario */
  --color-surface:          #1A1A1A;  /* Superficie de componentes */
  --color-surface-light:    #242424;  /* Superficie elevada */

  /* Tonalidades claras (texto) */
  --color-white:            #FFFFFF;  /* Texto principal */
  --color-light-gray:       #B0B0B0;  /* Texto secundario */
  --color-gray:             #888888;  /* Texto terciario */
  --color-text-muted:       #666666;  /* Texto desactivado */

  /* Bordes */
  --color-border:           #2A2A2A;  /* Borde por defecto */
  --color-border-hover:     rgba(255,90,31,0.3);  /* Borde hover */

  /* Acentos */
  --color-accent:           #FF5A1F;  /* Naranja principal */
  --color-accent-secondary: #D4AF37;  /* Dorado secundario */
}
```

**Esquema:** Fondo oscuro (`#0A0A0A`) con acentos en **naranja** (`#FF5A1F`) y **dorado** (`#D4AF37`), creando una estética tecnológica premium similar a publicaciones como Wired o The Verge.

### 🔤 Tipografías

| Fuente | Rol | Pesos |
|--------|-----|-------|
| **Space Grotesk** (`--font-display`) | Títulos, encabezados, números destacados | 400, 500, 600, 700 |
| **Inter** (`--font-primary`) | Texto corrido, botones, navegación | 300, 400, 500, 600 |

Ambas fuentes cargadas desde Google Fonts con `@import` en `main.css`.

### 📐 Variables de espaciado

```css
--spacing-xs:  0.375rem;   /*   6px */
--spacing-sm:  0.5rem;     /*   8px */
--spacing-md:  0.75rem;    /*  12px */
--spacing-lg:  1rem;       /*  16px */
--spacing-xl:  1.5rem;     /*  24px */
--spacing-2xl: 2rem;       /*  32px */
--spacing-3xl: 3rem;       /*  48px */
--spacing-4xl: 4rem;       /*  64px */
```

### 🔲 Componentes reutilizables

| Componente | Archivo CSS | Variantes |
|------------|-------------|-----------|
| **Botones** | `componentes.css` | `btn--primary`, `btn--secondary`, `btn--ghost`, `btn--sm`, `btn--lg` |
| **Article Card** | `componentes.css` | Con imagen, categoría flotante, autor, fecha, tiempo lectura |
| **Review Card** | `componentes.css` | Con estrellas, rating, imagen con zoom hover |
| **Event Card** | `componentes.css` | Con caja de fecha, layout horizontal/vertical |
| **Post** | `componentes.css` | Para foro comunitario, con avatar, acciones |
| **Badge/Tag** | `componentes.css` | `badge--accent` para etiquetas |
| **Form** | `componentes.css` | Input, textarea, select con focus glow |
| **Comment** | `componentes.css` | Para sección de comentarios |
| **Table Comparison** | `componentes.css` | Tabla de especificaciones |
| **FAQ** | `componentes.css` | Acordeón con `<details>` |
| **TOC** | `componentes.css` | Tabla de contenidos para artículos |

### 🎭 Animaciones

| Animación | Archivo | Tipo | Descripción |
|-----------|---------|------|-------------|
| `heroZoom` | `main.css` | `@keyframes` | Zoom de entrada 1.1→1 en 8s en la imagen del hero |
| `heroReveal` | `main.css` | `@keyframes` | FadeIn + translateY 40px→0 para contenido del hero |
| `fadeInUp` | `main.css` | `@keyframes` | Entrada suave para cards, 20px→0 |
| `fadeIn` | `main.css` | `@keyframes` | Aparición gradual |
| `scaleIn` | `main.css` | `@keyframes` | Escala 0.9→1 |
| `slideInLeft/Right` | `main.css` | `@keyframes` | Deslizamiento lateral |
| `loaderFade` | `main.css` | `@keyframes` | Parpadeo del loader 0.6s |
| `loaderLogo` | `main.css` | `@keyframes` | Entrada del logo en pantalla de carga |
| `loaderBar` | `main.css` | `@keyframes` | Barra de progreso 0→100% |
| `progressBar` | `main.css` | `@keyframes` | Barra de lectura scroll-driven |
| `scrollIndicator` | `main.css` | `@keyframes` | Rebote vertical infinito en indicador scroll |
| `float` | `main.css` | `@keyframes` | Flotación Y -10px para efectos decorativos |

### ✨ Microinteracciones (hover y transiciones)

| Elemento | Efecto |
|----------|--------|
| Article Card | Elevación `-4px` + sombra + borde naranja + zoom imagen 1.05 + título naranja |
| Review Card | Elevación `-4px` + sombra + zoom imagen 1.05 + título naranja |
| Event Card | Borde hover naranja |
| Post (comunidad) | Borde hover naranja |
| Botón primary | Fondo sólido → transparente con texto naranja |
| Botón secondary | Borde naranja con glow tenue |
| Sidebar filtros | Background highlight + color blanco |
| Footer social links | Elevación -2px + borde/bg naranja |
| Enlaces footer | Color naranja en hover |
| Tarjetas genéricas | Borde naranja + sombra |

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/responsive.png" width="28" style="vertical-align:middle"> Responsive Design

### Enfoque: Mobile First

El diseño se construye desde la **vista móvil** como base, y se potencian las capacidades visuales a medida que el viewport crece. Esto garantiza que el sitio funcione correctamente en cualquier dispositivo y que la experiencia en móvil no sea una ocurrencia tardía.

### Breakpoints utilizados

```css
/* Base:      0px   → 479px   – Móvil pequeño  */
/* 480px+  */  @media (min-width: 480px)   – Móvil grande
/* 640px+  */  @media (min-width: 640px)   – Tablet vertical
/* 768px+  */  @media (min-width: 768px)   – Tablet horizontal / Desktop pequeño
/* 850px+  */  @media (min-width: 850px)   – Desktop medio
/* 1024px+ */  @media (min-width: 1024px)  – Desktop grande
/* 1280px+ */  @media (min-width: 1280px)  – Pantallas extra grandes
```

### Comportamiento por dispositivo

| Viewport | Header | Hero | Grid artículos | Footer | Sidebar |
|----------|--------|------|----------------|--------|---------|
| **< 640px** | Hamburguesa | Apilado, texto centrado | 1 columna | 1 columna, centrado | Dentro del flujo |
| **640px+** | Menú horizontal | Ajuste de padding | 2 columnas | 2 columnas | Dentro del flujo |
| **768px+** | — | Altura completa (100vh) | 2 columnas | 4 columnas | Sticky (`position: sticky`) |
| **1024px+** | — | — | 3 columnas | 4 columnas | Sticky |

### Adaptaciones especiales

- **Categorías:** Layout de 2 columnas (sidebar 260px + contenido flexible) a partir de 768px
- **Formulario contacto:** `grid-template-columns: 1fr 1fr` a 2 columnas, colapsa a 1 en móvil
- **Event cards:** Layout horizontal en desktop, vertical en móvil
- **Comunidad + sidebar:** Grid 2 columnas (1fr + 280px) en desktop
- **Paginación:** Espaciado y tamaños aumentan en 850px+
- **Tabla comparativa:** Font-size reducido en móvil para evitar desborde

<br>

---

<br>

## ✨ Animaciones

### 🎬 Hero Section

El hero principal combina **3 animaciones coordinadas**:

1. **`heroZoom`** (8s): La imagen de fondo escala lentamente de 1.1 a 1, creando un efecto cinematográfico tipo Ken Burns
2. **`heroReveal`** (0.8s): Los elementos del contenido (tag, título, descripción, botones) aparecen secuencialmente con delays de 0.3s, 0.5s, 0.7s y 0.9s
3. **`scrollIndicator`** (2s): El indicador "Desliza" oscila verticalmente con opacidad variable, invitando al scroll

```css
.hero__image {
  animation: heroZoom 8s ease forwards;
}
.hero__tag     { animation: heroReveal 0.8s ease 0.3s both; }
.hero__title   { animation: heroReveal 0.8s ease 0.5s both; }
.hero__desc    { animation: heroReveal 0.8s ease 0.7s both; }
.hero__actions { animation: heroReveal 0.8s ease 0.9s both; }
```

### 🃏 Cards

Todas las cards (artículos, reseñas, eventos) comparten un patrón de animación:

| Estado | Propiedad | Valor |
|--------|-----------|-------|
| **Entrada** | `animation` | `fadeInUp 0.6s ease both` |
| **Hover** | `transform` | `translateY(-4px)` |
| **Hover** | `border-color` | `--color-border-hover` (naranja) |
| **Hover imagen** | `transform` | `scale(1.05)` en 0.6s |

### 🔘 Botones

| Botón | Hover | Transición |
|-------|-------|------------|
| `btn--primary` | Fondo → transparente, texto → naranja | 0.2s ease |
| `btn--secondary` | Borde → naranja, texto → naranja | 0.2s ease |
| `btn--ghost` | Texto → naranja | 0.2s ease |

### ⏳ Loading Screen

Pantalla de carga inicial con 3 animaciones encadenadas:

```
1. loaderLogo  →  logo aparece con fadeInUp (0.8s)
2. loaderBar   →  barra progresa 0→100% (1.2s, delay 0.3s)
3. loaderFade  →  pantalla completa se desvanece (0.6s, delay 1.8s, forwards)
```

### 📊 Progress Bar

Barra de progreso de lectura **scroll-driven** (navegador compatible):

```css
.progress-bar {
  animation: progressBar linear;
  animation-timeline: scroll();
}
```

> ⚠️ **Compatibilidad:** `animation-timeline: scroll()` es una característica experimental de CSS. En navegadores sin soporte, la barra permanece estática sin romper el diseño.

### 🔄 Transiciones globales

```css
--transition-fast: 0.2s ease;   /* Hovers, cambios de color */
--transition-base: 0.3s ease;   /* Paneles, menú */
--transition-slow: 0.5s ease;   /* Efectos decorativos */
```

<br>

---

<br>

## ♿ Accesibilidad

### HTML semántico

Todas las páginas utilizan landmarks de HTML5 (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) para facilitar la navegación por lectores de pantalla.

### Jerarquía de encabezados

```
h1 → Hero title (único por página)
h2 → Section titles, TOC title, FAQ title
h3 → Card titles, post titles, event titles
h4 → Footer heading
```

### Estados focus

```css
*:focus-visible {
  outline: 2px solid var(--color-accent);
  outline-offset: 2px;
}
```

### Skip-link

```html
<a href="#main-content" class="skip-link">Saltar al contenido principal</a>
```
```css
.skip-link { position: absolute; top: -100%; }
.skip-link:focus { top: var(--spacing-md); }
```

### Contraste

La paleta oscura garantiza una **relación de contratio superior a 7:1** entre el texto blanco (`#FFFFFF`) y el fondo oscuro (`#0A0A0A`), cumpliendo con el nivel AAA de WCAG.

### prefers-reduced-motion

```css
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}
```

### prefers-contrast

```css
@media (prefers-contrast: high) {
  :root {
    --color-border: #666;
    --color-text-muted: #aaa;
    --color-light-gray: #e0e0e0;
  }
}
```

### Otras prácticas

- **Alt text** descriptivo en todas las imágenes
- **ARIA labels** en elementos interactivos (hamburguesa, enlaces sociales)
- **Min-height 44px** en botones y enlaces para cumplir con objetivo táctil de WCAG
- **Resize vertical** permitido en textareas
- **Label conectado** a inputs mediante `for`/`id`

<br>

---

<br>

## 📂 Organización del CSS

La arquitectura CSS sigue un **enfoque modular** con 4 archivos independientes, cada uno con una responsabilidad única:

```
activos/css/
│
├── main.css           # ❶ FUNDACIÓN: Variables CSS, reset, keyframes, utilidades
├── layout.css         # ❷ ESTRUCTURA: Header, hero, grids, footer, sidebar, paginación
├── componentes.css    # ❸ COMPONENTES: Botones, cards, formularios, tablas, badges
└── responsive.css     # ❹ ADAPTACIÓN: Media queries Mobile First
```

### 📄 main.css (273 líneas)

| Sección | Contenido |
|---------|-----------|
| `@import` | Google Fonts (Space Grotesk + Inter) |
| `:root` | 30+ variables CSS (colores, tipografías, espaciados, radios, sombras, transiciones) |
| Reset | Box-sizing, margin/padding reset, scroll-behavior, scrollbar personalizada |
| Keyframes | 12 animaciones `@keyframes` |
| Utilidades | `.container`, `.section`, `.section__header`, `.gradient-text`, `.visually-hidden` |

> ⚡ **Clave:** Las variables CSS permiten cambiar toda la paleta del sitio modificando solo los valores en `:root`.

### 📄 layout.css (778 líneas)

| Sección | Función |
|---------|---------|
| Loader | Pantalla de carga con logo + barra de progreso |
| Progress Bar | Barra de lectura scroll-driven |
| Header/Nav | Sticky header con backdrop-filter blur, hamburguesa checkbox hack |
| Hero | Hero cinematográfico con overlay degradado |
| Trending | Strip horizontal de tendencias |
| Story Section | Grid de 2 columnas con estadísticas |
| Grids | `grid-articles`, `grid-categories`, `grid-reviews`, `grid-events`, `grid-footer` |
| Sidebar | Búsqueda, filtros, sticky positioning |
| Pagination | Paginación con estados active/hover |
| Footer | 4-columnas, enlaces, legal, redes sociales |

### 📄 componentes.css (982 líneas)

| Sección | Componentes |
|---------|-------------|
| Buttons | `.btn`, `.btn--primary`, `.btn--secondary`, `.btn--ghost`, `.btn--sm`, `.btn--lg` |
| Article Card | `.article-card` con imagen, categoría flotante, meta, hover efectos |
| Review Card | `.review-card` con estrellas, rating |
| Comparison Table | `.table-comparison` para especificaciones |
| Comment | `.comment` con avatar, acciones |
| Form | `.form__group`, `.form__input`, `.form__textarea`, `.form__select` |
| Event Card | `.event-card` con date-box |
| Post | `.post` para foro comunitario |
| FAQ | `.faq__item` con details/summary |
| Badge | `.badge`, `.badge--accent` |
| Article Hero | `.article-hero`, `.toc`, `.article-body` con tipografía de lectura |
| Accessibility | `.skip-link`, `:focus-visible`, `prefers-reduced-motion`, `prefers-contrast` |

### 📄 responsive.css (219 líneas)

| Breakpoint | Cambios principales |
|------------|---------------------|
| 480px+ | Hero font-size, stats 3 columnas |
| 640px+ | Menú horizontal, grids 2 columnas, hero padding |
| 768px+ | Hero 100vh, sidebar sticky, footer 4 columnas |
| 850px+ | Paginación expandida |
| 1024px+ | Grids 3 columnas, section padding aumentado |
| 1280px+ | Gaps incrementados en grids |

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/git.png" width="28" style="vertical-align:middle"> Flujo de trabajo

### Git Flow

El proyecto se desarrolló siguiendo la metodología **Git Flow**, con una estructura de ramas que separa el desarrollo estable de las características en progreso:

<div align="center">

```
main  ───●──────────────────────────────────────●── (release v1.0.0)
          \                                    /
develop ──●──●──●──●──●──●──●──●──●──●──●────●──
          |   |   |   |   |   |   |   |   |
          f1  f2  f3  f4  f5  f6  f7  f8  f9
```

</div>

### Ramas

| Rama | Propósito | Commits |
|------|-----------|---------|
| **`main`** | Versión estable y publicada. Solo recibe merges desde `develop` | 2 (init + release) |
| **`develop`** | Integración de todas las características. Rama activa principal | 8 merges con `--no-ff` |
| **`feature/*`** | Desarrollo de funcionalidades individuales. Se crean desde `develop` y se eliminan tras merge | 7 branches (24 commits totales) |

### Feature branches

| Rama | Commits | Descripción |
|------|---------|-------------|
| `feature/inicio` | 6 | `:tada:` init → `:lipstick:` CSS system → `:sparkles:` header → `:bento:` images → `:lipstick:` hero → `:sparkles:` home page |
| `feature/categorias` | 1 | `:sparkles:` Sidebar, filtros, 15 artículos, paginación |
| `feature/resenas` | 1 | `:sparkles:` Review cards, tabla comparativa, comentarios |
| `feature/comunidad` | 1 | `:sparkles:` Foro, FAQ, badges |
| `feature/eventos` | 1 | `:sparkles:` Event cards, CTA banner |
| `feature/contacto` | 1 | `:sparkles:` Formulario, tarjetas info, mapa |
| `feature/articulo` | 1 | `:sparkles:` Artículo individual con TOC |
| `feature/responsive` | 3 | `:iphone:` Responsive → `:wheelchair:` Accesibilidad → `:mag:` SEO |
| `feature/documentacion` | 1 | `:memo:` README y documentación |

### Conventional Commits

Cada commit sigue el formato `:emoji: tipo(alcance): descripción`.

| Emoji | Tipo | Significado |
|-------|------|-------------|
| `:tada:` | `chore` | Inicialización del proyecto |
| `:sparkles:` | `feat` | Nueva funcionalidad |
| `:lipstick:` | `style` | Estilos CSS, diseño visual |
| `:bento:` | `assets` | Imágenes y recursos |
| `:iphone:` | `responsive` | Adaptaciones responsive |
| `:wheelchair:` | `a11y` | Mejoras de accesibilidad |
| `:mag:` | `seo` | Optimización SEO |
| `:memo:` | `docs` | Documentación |
| `:rocket:` | `release` | Versión publicada |

### Flujo de merge

Cada feature branch sigue este ciclo:

```bash
git checkout develop
git checkout -b feature/nombre

# ... trabajo y commits ...

git checkout develop
git merge feature/nombre --no-ff -m ":sparkles: feat(nombre): merge description"
git branch -d feature/nombre
git push origin develop
```

> **`--no-ff`** garantiza que quede un commit de merge visible en el historial, preservando la traza de la rama feature incluso después de eliminarla.

### Versionado

| Versión | Rama | Descripción |
|---------|------|-------------|
| `v0.1.0` | `develop` | Iteración inicial con 6 features |
| `v0.2.0` | `develop` | Features: resenas, comunidad, eventos, contacto, articulo |
| `v0.3.0` | `develop` | Responsive + accesibilidad + SEO |
| `v1.0.0` | `main` | Release final con documentación completa |

<br>

---

<br>

## <img src="https://img.icons8.com/fluency/48/null/installation.png" width="28" style="vertical-align:middle"> Instalación

### Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Git (opcional, solo para clonar)
- Live Server (opcional, para recarga en caliente)

### Pasos

```bash
# 1. Clonar el repositorio
git clone https://github.com/santiagosanabria-1/proyecto-web-j2-santiago-sanabria.git

# 2. Entrar al directorio
cd proyecto-web-j2-santiago-sanabria

# 3. Abrir en el navegador
start index.html                    # Windows
open index.html                     # macOS
xdg-open index.html                 # Linux
```

### Con Live Server (recomendado)

```bash
# Usando VS Code
code .                              # Abrir proyecto
# Instalar extensión "Live Server"
# Click derecho en index.html → "Open with Live Server"
```

> 💡 **Consejo:** El proyecto incluye configuración de Live Preview en `.vscode/settings.json` con `livePreview.defaultPreviewPath: "/index.html"`.

### Verificar funcionamiento

Una vez abierto en el navegador, se debe ver:

1. **Pantalla de carga** con animación de barra de progreso (aprox. 1.8s)
2. **Hero cinematográfico** con zoom de fondo y texto que aparece secuencialmente
3. **Navegación** con menú hamburguesa en móvil y menú horizontal en desktop
4. **6 páginas** accesibles desde el menú de navegación y enlaces del footer
5. **Responsive** completo al redimensionar la ventana

<br>

---

<br>

## 📸 Capturas

> *Las capturas de pantalla del proyecto serán añadidas en futuras actualizaciones.*

Las imágenes de ejemplo del proyecto se encuentran en:

```
activos/img/
├── articulos/      → 15 imágenes de artículos (IA, gaming, ciberseguridad, etc.)
├── reseñas/        → 6 imágenes de productos (smartphones, laptops, etc.)
├── hero/           → Hero banner principal
├── eventos/        → Imagen de conferencia tecnológica
└── contacto/       → Captura de mapa de ubicación
```

<br>

---

<br>

## 🚀 Posibles mejoras futuras

| Mejora | Descripción | Tecnología necesaria |
|--------|-------------|---------------------|
| 🌙 **Modo oscuro/claro** | Alternancia de tema con CSS custom properties y `prefers-color-scheme` | CSS + JS |
| ⚙️ **Backend** | Panel de administración para gestionar artículos, reseñas y eventos | Node.js / Python |
| 🗄️ **Base de datos** | Almacenamiento persistente de artículos, usuarios y comentarios | PostgreSQL / MongoDB |
| 👥 **Autenticación** | Registro e inicio de sesión con roles (admin, editor, usuario) | JWT + OAuth |
| 💬 **Comentarios reales** | Sistema de comentarios con votos, respuestas y moderación | Backend + DB |
| 🔍 **Buscador dinámico** | Búsqueda en tiempo real con filtros combinados | JavaScript + API |
| ⭐ **Sistema de rating** | Votación de artículos y reseñas por parte de usuarios | JS + Backend |
| 🎨 **Temas personalizados** | Selección de paleta de colores por el usuario | CSS variables + JS |
| 📱 **PWA** | Aplicación web progresiva con instalación y offline | Service Workers |
| 🌐 **Internacionalización** | Soporte multi-idioma (es, en, pt) | i18n + HTML |
| 🧪 **Testing** | Pruebas de regresión visual y accesibilidad | Playwright / Cypress |
| 🚄 **SSR / SSG** | Generación de páginas estáticas para mejorar SEO | Astro / 11ty |

<br>

---

<br>

## 👤 Autor

<div align="center">

**Santiago Sanabria**
</div>
<div align="center">
  <b>Frontend Developer</b>
</div>
<div align="center">
  Proyecto académico — Skill HTML + CSS
</div>
<div align="center">
  2026
</div>

<br>

---

<br>

## 📝 Licencia

```
MIT License

Copyright (c) 2026 Santiago Sanabria

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<p align="center">
  <sub>Construido con ❤️ y puro CSS, sin frameworks, sin JavaScript.</sub>
</p>

<p align="center">
  <a href="https://github.com/santiagosanabria-1/proyecto-web-j2-santiago-sanabria">🌐 Ver en GitHub</a>
</p>
