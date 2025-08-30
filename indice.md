## 1. Selectores Combinados y Especiales

Algunos de los selectores más usados en CSS:

- **Descendiente**: `div p` → selecciona los `p` dentro de un `div`.
- **Hijo directo**: `div > p` → selecciona solo los `p` hijos directos.
- **Hermano adyacente**: `h1 + p` → selecciona el `p` que va justo después de un `h1`.
- **Hermano general**: `h1 ~ p` → selecciona todos los `p` que son hermanos de `h1`.
- **Atributo**:
  - `[type="text"]` → selecciona input con type text.
  - `[href^="https"]` → comienza con `https`.
  - `[href$=".pdf"]` → termina en `.pdf`.
  - `[class*="btn"]` → contiene la palabra `btn`.

🔗 [Documentación MDN – Selectores CSS](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Selectors)

---

## 2. Pseudoclases Destacadas

Algunas pseudoclases muy útiles:

- `:hover`
- `:active`
- `:focus`
- `:first-child` y `:last-child`
- `:nth-child(n)`
- `:not(selector)`
- `:has(selector)`

🔗 [Lista completa de pseudoclases en MDN](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes)

---

## 3. Propiedades de Texto

- `color`
- `font-family`
- `font-size`
- `font-weight`
- `text-align`
- `line-height`
- `letter-spacing`
- `text-decoration`
- `text-transform`

🔗 [Propiedades de texto en MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Text)

---

## 4. Modelo de Cajas (Box Model)

- `width`, `height`
- `padding`
- `margin`
- `border` (`border-style`, `border-width`, `border-color`)
- `box-sizing`
- `overflow`

🔗 [Modelo de caja en MDN](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model)

---

## 5. Unidades y Medidas

- **Absolutas**: `px`, `pt`, `cm`.
- **Relativas**: `%`, `em`, `rem`, `vw`, `vh`, `vmin`, `vmax`.

🔗 [Unidades en MDN](https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Values_and_units)

---

## 6. Posicionamiento

- `position: static`
- `position: relative`
- `position: absolute`
- `position: fixed`
- `position: sticky`
- `z-index`

🔗 [Guía de posicionamiento en MDN](https://developer.mozilla.org/es/docs/Web/CSS/position)

---

## 7. Flexbox

Propiedades principales del contenedor:

- `display: flex`
- `flex-direction`
- `justify-content`
- `align-items`
- `align-content`
- `gap`

Propiedades en los ítems:

- `flex`
- `order`
- `align-self`

🔗 [Guía completa de Flexbox en MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

---

## 8. Grid

Propiedades del contenedor:

- `display: grid`
- `grid-template-columns`
- `grid-template-rows`
- `gap`
- `grid-auto-flow`

Propiedades en los ítems:

- `grid-column`
- `grid-row`

🔗 [Guía de CSS Grid en MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout)

---

## 9. Responsive Design

- `@media` → consultas de medios.
- Unidades relativas (`%`, `em`, `rem`, `vw`, `vh`).
- Mobile first.

Ejemplo:

```css
@media (max-width: 768px) {
  body {
    background: lightblue;
  }
}
```
