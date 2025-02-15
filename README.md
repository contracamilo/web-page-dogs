# Documentación del Proyecto: Sitio Web de Adopción de Perros

## 1. Introducción

Este proyecto consiste en un sitio web para la adopción de perros, desarrollado utilizando únicamente HTML y CSS. Se ha diseñado considerando buenas prácticas de desarrollo web, tales como:

- **HTML semántico**
- **Accesibilidad**
- **Optimización de imágenes**
- **Animaciones con keyframes**
- **Organización del CSS mediante la metodología BEM**
- **Código comentado**
- **Integración de Google Fonts**
- **Responsive design**
- **Performance**
- **SEO**

---

## 2. Estructura del Proyecto

El proyecto se compone de dos archivos principales:

- `index.html`: Contiene la estructura y el contenido del sitio web.
- `styles.css`: Contiene los estilos, animaciones y reglas de responsive design.

---

## 3. HTML Semántico

El código HTML utiliza etiquetas semánticas que ayudan a definir la estructura y el contenido del sitio, facilitando la interpretación tanto por navegadores como por motores de búsqueda y tecnologías de asistencia. Algunas etiquetas utilizadas son:

- `<header>`: Define la cabecera del sitio, donde se incluye la navegación principal.
- `<nav>`: Se usa para agrupar enlaces de navegación.
- `<main>`: Contiene el contenido principal del sitio.
- `<section>`: Agrupa bloques temáticos, como la sección "Hero", la sección de adopción y la sección de contacto.
- `<article>`: Se utiliza para cada tarjeta o entrada individual de perro disponible para adopción.
- `<footer>`: Define el pie de página del sitio.

---

## 4. Accesibilidad

Se han implementado diversas prácticas para mejorar la accesibilidad:

- Uso de atributos `alt` en las imágenes para describir su contenido.
- Uso de etiquetas `<label>` asociadas a los campos de formulario.
- Estructura semántica del HTML que facilita la navegación con lectores de pantalla.
- Buen contraste de colores y tamaños de fuente legibles.

---

## 5. Imágenes Optimizadas

Aunque las imágenes deben optimizarse mediante herramientas externas (por ejemplo, TinyPNG o ImageOptim), en el código se han incluido atributos `width` y `height` para reservar el espacio y mejorar la carga y el rendimiento del sitio.

---

## 6. Animaciones con Keyframes

Se ha implementado una animación en la imagen del "Hero" utilizando la regla `@keyframes`:

- **`fadeIn`**: Anima la opacidad y el desplazamiento vertical para lograr un efecto de entrada suave.

Esta animación mejora la experiencia visual sin afectar significativamente el rendimiento.

---

## 7. Organización del CSS con la Metodología BEM

Se ha utilizado la metodología **BEM (Block Element Modifier)** para nombrar las clases en el CSS. Esta metodología ayuda a:

- Mantener el código organizado.
- Facilitar la escalabilidad y el mantenimiento.
- Evitar conflictos de estilos mediante una convención de nombres clara.

Ejemplos de clases siguiendo BEM en el proyecto son: `header__nav-list`, `tarjeta__body` y `contacto__form`.

---

## 8. Código Comentado

El código tanto en HTML como en CSS contiene comentarios que explican la función y el propósito de cada sección. Esto facilita la comprensión del proyecto por parte de otros desarrolladores y mejora el mantenimiento del código a lo largo del tiempo.

---

## 9. Uso de Google Fonts

Se ha integrado la fuente **"Roboto"** mediante Google Fonts para mejorar la tipografía del sitio, asegurando una presentación moderna y legible en diferentes dispositivos.

---

## 10. Responsive Design

Se han utilizado media queries en el CSS para adaptar el diseño a diferentes tamaños de pantalla. Esto permite que el sitio se visualice correctamente tanto en dispositivos de escritorio como en móviles, garantizando una experiencia de usuario óptima.

Ejemplo:
```css
@media (max-width: 768px) {
  .header__nav-list {
    flex-direction: column;
    gap: 0.5rem;
  }
  
  .hero__title {
    font-size: 1.75rem;
  }
  
  .adopcion__grid {
    grid-template-columns: 1fr;
  }
}
```

---

## 11. Performance y SEO

### Performance

- **Optimización de recursos:** Se recomienda minificar los archivos CSS y HTML para reducir el tiempo de carga.
- **Imágenes optimizadas:** Uso de atributos `width` y `height` para evitar el cambio de diseño al cargar las imágenes.
- **Animaciones eficientes:** Las animaciones están diseñadas para ser suaves y no afectar el rendimiento.

### SEO

- **Metaetiquetas:** Se han incluido metaetiquetas importantes como `<meta charset="UTF-8">`, `<meta name="viewport">` y `<meta name="description">` para ayudar a los motores de búsqueda a indexar correctamente el sitio.
- **HTML semántico:** El uso de etiquetas semánticas mejora la accesibilidad y el posicionamiento en buscadores.

---

## 12. Buenas Prácticas

El proyecto sigue varias buenas prácticas de desarrollo web:

- **Código limpio y organizado:** Tanto el HTML como el CSS están estructurados y comentados.
- **Metodologías de nombrado:** Uso de BEM para clases en el CSS.
- **Accesibilidad:** Se han tomado medidas para que el sitio sea accesible para todos los usuarios.
- **Responsive y performance:** Se han implementado técnicas para mejorar la experiencia de usuario en diferentes dispositivos y optimizar la carga del sitio.

---

## Conclusión

Esta documentación detalla cómo se han implementado y organizado los diferentes aspectos técnicos del sitio web de adopción de perros. Se han aplicado conceptos modernos y buenas prácticas en el desarrollo web para garantizar un producto final accesible, rápido, y de fácil mantenimiento, optimizado tanto para usuarios como para motores de búsqueda.
