Markdown# Disney Webpage Educational Project

Este sitio web ha sido construido exclusivamente con fines educativos y académicos, para compartir y evaluar los conocimientos de los estudiantes en un entorno cercano al ámbito profesional. Sirve como una práctica para reforzar las habilidades en HTML y CSS, simulando flujos de trabajo reales de desarrollo web.

---

## 👥 Integrantes del Equipo
* **Sebastian Medellin Quintero**
* **Luis Fernando Piamba Lugo**

---

## 1. HTML Structure Overview
```html
<!DOCTYPE html><html lang="en"><head>…</head><body>
  <nav class="navbar">…</nav>
  <section class="banner">…</section>
  <main>
    <section id="shop">…</section>
    <section id="disney-plus">…</section>
    <section id="movies">…</section>
    <section id="parks-and-travel">…</section>
    <section id="more">…</section>
  </main>
  <footer>…</footer></body></html>
Key Semantic Tags   <!DOCTYPE html>: Declara HTML5 para un renderizado consistente en los navegadores.   <html lang="en">: Ayuda a los lectores de pantalla y motores de búsqueda a identificar el idioma.<head>: Contiene metadatos (juego de caracteres, configuración de viewport, título y enlaces a hojas de estilo).<nav>: Define la sección principal de navegación.<section>: Organiza agrupaciones temáticas de contenido (banner, tienda, Disney+, películas, parques, ofertas).<article>: Representa bloques de contenido independientes e ideales para reutilizar (tarjetas de tienda, destaques).<main>: Indica el área de contenido principal y única por página.<footer>: Contiene la navegación secundaria y los avisos legales.2. Essential CSS PropertiesCSS/* Global Reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
box-sizing: border-box: Incluye el relleno (padding) y los bordes (border) dentro del ancho y alto definidos de un elemento, simplificando los cálculos de diseño.display: flex / justify-content / align-items: Crea diseños flexibles y unidimensionales (utilizados en la barra de navegación, banner y contenedores de tarjetas).background-size: cover, background-position: center, background-repeat: no-repeat: Aseguran que las imágenes de fondo cubran por completo sus contenedores manteniendo los puntos focales.flex-direction: column: Apila los elementos hijos verticalmente.gap, margin, padding: Administran el espaciado consistente entre y dentro de los elementos.Unidades relativas (%, rem, vh): Permiten diseños fluidos y adaptables a diferentes tamaños de pantalla.3. Best Practices and Professional TipsSemantic Markup: Uso de etiquetas HTML adecuadas para mejorar la accesibilidad y el SEO.Mobile-First & Responsive Units: Inicio con estilos base y adaptación mediante media queries, empleando rem y %.Modular CSS Architecture: Organización de estilos en capas lógicas y adopción de convenciones de nomenclatura limpias.Optimized Images: Carga optimizada de recursos visuales y uso de propiedades adaptativas en los fondos de CSS.Accessibility (a11y): Inclusión de atributos alt descriptivos y contraste de color adecuado para mejorar la experiencia de usuario.Este README guía a través de la estructura central y las decisiones de diseño adoptadas por el equipo para cumplir con los estándares de desarrollo web moderno.
