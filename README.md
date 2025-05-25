# Sitio Web de Tecnologías Cloud

Este proyecto es un sitio web informativo sobre Tecnologías Cloud, diseñado para ser visualmente atractivo e interactivo mediante el uso de diversas animaciones CSS.

## Características Principales

*   **Diseño Responsivo**: Adaptado para una visualización óptima en dispositivos móviles y de escritorio.
*   **Animaciones CSS Avanzadas**:
    *   **Slider Automático**: En la página principal, mostrando servicios destacados.
    *   **Efecto Parallax**: Aplicado en varias secciones para crear una sensación de profundidad.
    *   **Galería de Imágenes Interactiva**: Con efectos de hover, zoom y visualización modal.
*   **Estructura de Seis Páginas**:
    *   Inicio (`index.html`)
    *   Servicios (`pages/servicios.html`)
    *   Tecnologías (`pages/tecnologias.html`)
    *   Galería (`pages/galeria.html`)
    *   Nosotros (`pages/nosotros.html`)
    *   Contacto (`pages/contacto.html`)
*   **Imágenes Externas**: Utiliza imágenes de Unsplash para el contenido visual.

## Tecnologías Utilizadas

*   HTML5
*   CSS3 (Animaciones, Flexbox, Grid)
*   JavaScript (para interactividad básica como el slider y la galería)
*   Diseño Responsivo (Media Queries)

## Estructura del Proyecto

```
tecnologias-cloud-website/
├── index.html                # Página de Inicio
├── README.md                 # Este archivo
├── css/                      # Hojas de estilo
│   ├── style.css             # Estilos generales y base
│   ├── gallery.css           # Estilos para la página de Galería
│   ├── parallax.css          # Estilos para el efecto Parallax
│   └── slider.css            # Estilos para el carrusel de imágenes
├── image/                    # Imágenes locales del proyecto (si las hubiera, actualmente usa URLs)
└── pages/                    # Páginas secundarias
    ├── contacto.html         # Página de Contacto
    ├── galeria.html          # Página de Galería de imágenes
    ├── nosotros.html         # Página Sobre Nosotros
    ├── servicios.html        # Página de Servicios
    └── tecnologias.html      # Página de Tecnologías
```

## Animaciones CSS Implementadas

1.  **Slider CSS (Carrusel)**
    *   Ubicación: Página principal ([`index.html`](index.html)).
    *   Descripción: Un carrusel de imágenes que rota automáticamente utilizando `keyframes` y transiciones CSS para mostrar diferentes aspectos o servicios de la empresa.
2.  **Efecto Parallax**
    *   Ubicación: Secciones destacadas en varias páginas (ej. [`index.html`](index.html), [`pages/servicios.html`](pages/servicios.html), [`pages/nosotros.html`](pages/nosotros.html), [`pages/tecnologias.html`](pages/tecnologias.html), [`pages/contacto.html`](pages/contacto.html)).
    *   Descripción: Crea un efecto de profundidad visual donde el fondo se desplaza a una velocidad diferente que el contenido principal al hacer scroll.
3.  **Galería de Imágenes con CSS**
    *   Ubicación: Página de Galería ([`pages/galeria.html`](pages/galeria.html)).
    *   Descripción: Presenta un conjunto de imágenes con efectos interactivos al pasar el cursor (hover), como zoom y superposiciones de información. Podría incluir una visualización modal al hacer clic (verificar implementación JS si es avanzada).

## Cómo Empezar

1.  **Clonar el Repositorio**:
    ```bash
    git clone https://github.com/Omar-Cc/CloudTech.git
    cd tecnologias-cloud-website
    ```
2.  **Abrir el Sitio**:
    *   Navega a la carpeta del proyecto.
    *   Abre el archivo [`index.html`](index.html) en tu navegador web preferido.
3.  **Navegación**:
    *   Utiliza el menú de navegación principal para explorar las diferentes páginas del sitio.

## Requisitos Previos

*   Un navegador web moderno (ej. Chrome, Firefox, Safari, Edge).
*   Conexión a internet (necesaria para cargar las imágenes desde Unsplash y otros CDNs de iconos).

## Créditos

*   **Diseño y Desarrollo**: Omar Ccerhuayo
*   **Imágenes**: Obtenidas de [Unsplash](https://unsplash.com/)
*   **Iconos**: Algunos iconos pueden provenir de [Flaticon](https://www.flaticon.com/) u otros servicios similares.

---

© 2025 CloudTech
