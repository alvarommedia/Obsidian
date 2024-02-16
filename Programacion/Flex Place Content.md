---
tags:
  - CSS
  - Flex
links: "[[CSS]]"
---
**Flex Place Content** es una propiedad de [[FlexBox|flex]], la cual une las propiedades [[Flex Align Content]] y [[Flex Justify Content]].

Formas de declarar el **gap**:
- *Un valor*: Se establece el mismo valor para [[Flex Align Content|align content]] como para [[Flex Justify Content|justify content]].
- *Dos valores*: El primer valor establece el valor de [[Flex Align Content|align content]] y el segundo valor de [[Flex Justify Content|justify content]].

```css
.contenedor {
	display: flex;
	place-content: start end;
}
```