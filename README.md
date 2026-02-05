# The Amazing Coffee Shop — Sprint 3 (Parte 2)

Sitio web estático de una cafetería desarrollado como parte del **Proyecto del Sprint 3 (Parte 2)**. El objetivo fue maquetar la página según el brief, aplicar estilos con CSS, conectar tipografías desde Google Fonts y organizar el proyecto con una estructura de carpetas clara.

---

## Descripción del proyecto

La página incluye:

- **Header** con logotipo, navegación y contenido principal (título, descripción e imagen).
- **Sección de reserva** con formulario (validaciones HTML5) y **fondo decorativo**.
- **Sección de contactos** (ancla para navegación).
- **Footer** con logotipo, bloque de redes sociales, íconos y copyright.

---

## Funcionalidades implementadas

- Navegación interna mediante anclas (`#reservation`, `#contacts`).
- Formulario de reserva con validaciones nativas:
  - `required`, `minlength/maxlength`, `min/max`, `type="email"`, `type="datetime-local"`.
- Estilos y maquetación con CSS:
  - Posicionamiento (`relative/absolute`) en header y footer según el layout.
  - Fondo con imagen SVG en la sección de reserva usando `background-image`.
  - Interacciones de enlaces (hover) en navegación y redes sociales.
- Tipografías conectadas desde **Google Fonts**:
  - `Inter` (texto general)
  - `Noto Serif` (acentos/estilo editorial)

---

## Tecnologías usadas

- **HTML5**
- **CSS3**
- **Normalize.css**
- **Google Fonts** (`Inter`, `Noto Serif`)
- Metodología de nombres tipo **BEM** (clases con bloques/elementos)

---

## Estructura del proyecto

```txt
WEB_PROJECT_COFFEESHOP_ES/
  index.html
  README.md
  .editorconfig
  .gitignore
  .prettierignore
  favicon.ico
  images/
    background_reservation.svg
    inside_coffee_shop.png
    logo_coffeeshop_dark.svg
    logo_coffeeshop_light.svg
    facebook_white.svg
    instagram_white.svg
    check.svg
  styles/
    normalize.css
    index.css
  fonts/ (si aplica según checklist/brief)

```
