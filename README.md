# Fundamentos de CSS Moderno & Arquitectura Responsive

Este repositorio documenta mi ruta de aprendizaje práctico sobre los pilares fundamentales de **CSS3 puro**, enfocada en construir interfaces escalables, accesibles y adaptables antes de dar el salto a frameworks de utilidades como **Tailwind CSS**.

Cada rama (`branch`) representa un laboratorio práctico aislado donde se pusieron a prueba conceptos específicos de maquetación y flujo del navegador.

---

## Módulos y Prácticas Realizadas

### 1. Fundamentos, Cascada y Modelo de Caja (`Box Model`)
* **Cascada y Especificidad (`cascada`):** Resolución de conflictos de estilos, herencia y control del flujo natural.
* **Modelo de Caja (`Modelo-Caja`, `box-model/*`):** Uso estricto de `box-sizing: border-box`, control de márgenes, rellenos, `outline` y microinteracciones (`:hover`, `:active`, `:focus-within`).
* **Proyectos clave:** Tarjeta de perfil, factura digital y tarjeta de producto avanzada.

### 2. Posicionamiento y Flujos (`Position`)
* **Posicionamiento Avanzado (`Posicionamiento`, `position/*`):** Manejo de contextos de apilamiento (`z-index`), elementos fijos (`sticky`), posicionamiento absoluto relativo a contenedores y creación de una **ventana modal funcional con CSS puro** sin JavaScript.

### 3. Unidades Relativas y Funciones Matemáticas (`Units` & `Math`)
* **Unidades Fluidas (`units/*`):** Implementación de `rem`, `%`, `vh` y `vw` para tipografías, tarjetas responsivas y secciones *Hero* de pantalla completa (`min-height: 100vh`).
* **Cálculos Dinámicos y Variables (`layout/dashboard-fixed-sidebar`, `layout/dynamic-smart-container`):** 
  * Uso de Custom Properties (`:root`) con valores de respaldo (*fallbacks*).
  * Diseño fluido sin media queries mediante `calc()`, `min()`, `max()` y `clamp()`.

### 4. Diseño Responsivo (`Mobile-First` & `Media Queries`)
* **Estrategia Mobile-First (`layout/responsive-nav-flexbox`, `layout/classic-page-structure`):** Maquetación base pensada para dispositivos móviles y adaptación progresiva hacia pantallas de escritorio mediante breakpoints estándar (`min-width`).

### 5. Arquitectura con Flexbox y CSS Grid
* **Flexbox (`FlexBox/*`):** Control de distribución espacial mediante `flex-grow`, `flex-shrink`, `flex-basis` y `flex-wrap` (barra de búsqueda adaptable y tarjetas fluidas).
* **CSS Grid (`Grid/*`, `layout/grid-card-gallery`):** 
  * Cuadrículas intrínsecas con `repeat(auto-fit, minmax())`.
  * Posicionamiento explícito por líneas (`grid-column` / `grid-row`) y expansión asimétrica con `span` (estructura de página completa y diseño tipo **Bento Box**).

---

## Stack y Metodología
* **Tecnologías:** HTML5 Semántico, CSS3 Nativo (sin preprocesadores ni librerías).
* **Control de Versiones:** Git Flow basado en ramas por característica/concepto (`feature branches`) y Pull Requests integrados a `main`.
