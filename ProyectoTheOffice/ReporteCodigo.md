# Reporte Técnico del Código — Fan Page _The Office_

### Autor: **Adan Ballesillo Velazquez**

### Docente: **Pedro Espinosa Esparza**

### Fecha: **23/10/2025**

---

## Descripción General del Código

El código desarrollado para la fan page de _The Office_ está compuesto por tres archivos principales de estructura HTML (`index.html`, `personajes.html` y `contacto.html`), junto con hojas de estilo en **CSS3**, **Bootstrap 5** y **Tailwind CSS**.

El objetivo del código fue construir una página moderna, responsiva y visualmente atractiva, que sirviera como homenaje a la serie _The Office_, permitiendo navegar entre diferentes secciones y visualizar información sobre los personajes y frases icónicas.

---

Cada archivo cumple una función específica dentro del sitio:

| Archivo               | Función principal                                                             |
| --------------------- | ----------------------------------------------------------------------------- |
| `index.html`          | Página principal con la portada, introducción y frases célebres.              |
| `personajes.html`     | Muestra la galería de personajes, tarjetas y modales informativos.            |
| `contacto.html`       | Contiene el formulario de contacto con campos básicos de envío.               |
| `style.css`           | Define la apariencia visual general (colores, botones, hero section, footer). |
| `stylepersonajes.css` | Estiliza la galería y los modales de los personajes.                          |

---

## Descripción del Código por Componentes

### 1. Estructura HTML

El HTML de cada página se desarrolló siguiendo una **estructura semántica**.  
Se utilizaron etiquetas como `<header>`, `<main>`, `<section>`, `<article>` y `<footer>` para organizar el contenido y facilitar su lectura tanto por usuarios como por navegadores.

**Características principales:**

- Uso de etiquetas semánticas para mejorar la accesibilidad.
- Inclusión de un sistema de navegación `<nav>` con enlaces a todas las páginas.
- División del contenido en secciones temáticas (hero, frases, galería, formulario, etc.).
- Inclusión de clases de Bootstrap y Tailwind para control de diseño (`container`, `row`, `col`, `flex`, `text-center`, `p-4`, etc.).

---

### 2. Estilos CSS (style.css y stylepersonajes.css)

Los archivos CSS definen la **identidad visual** del sitio.

**Principales acciones realizadas:**

- Se aplicó una **paleta de colores** basada en tonos azul, blanco y amarillo.
- Se definieron variables globales (`--azul`, `--amarillo`, `--gris`, etc.) para mantener consistencia cromática.
- Se personalizaron botones, márgenes, bordes redondeados y efectos hover.
- Se diseñó la sección _hero_ con un fondo llamativo, centrado en texto y botones de acción.
- Se agregaron estilos específicos para el footer y las frases icónicas.
- En `stylepersonajes.css`, se dio formato a las **tarjetas de personajes**, incluyendo tamaños de imagen, tipografía y animaciones.
- Se implementaron **efectos de transición** (`transition`, `transform`, `box-shadow`) para lograr una interacción más dinámica.

---

### 3. Uso de Bootstrap 5

Bootstrap fue empleado para:

- La **maquetación general** del sitio mediante su sistema de **rejilla (Grid System)**.
- Creación de **tarjetas (cards)** con imágenes y texto.
- Implementación de **modales (modals)** para ampliar la información de los personajes.
- Garantizar **responsividad** en móviles, tabletas y pantallas grandes sin necesidad de mucho CSS adicional.

Clases comunes utilizadas:

```html
<div class="container text-center">
  <div class="row">
    <div class="col-md-4">
      <div class="card">...</div>
    </div>
  </div>
</div>
```

### Conclusión

_El proyecto logró cumplir su propósito de crear una fan page visualmente atractiva, funcional y adaptable.
Gracias al uso combinado de Bootstrap y Tailwind, se consiguió una interfaz moderna y ligera, manteniendo la esencia de la serie The Office.
La estructura del código facilita la futura integración de más secciones o componentes dinámicos._
