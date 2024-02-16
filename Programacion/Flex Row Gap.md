---
tags:
  - CSS
  - Flex
aliases:
  - row gap
links: "[[CSS]]"
---
La propiedad **Flex Row Gap** establece el espacio que tendrán los elementos hijo de un contenedor [[FlexBox|flex]] entre sí.

Esta propiedad tan solo funciona en aquellos contenedores que tengan una [[Flex Direction|flex direction]] de *column* o un [[Flex Wrap|flex wrap]] con un valor definido a *wrap*.

```css
.contenedor {
	display: flex;
	row-gap: 20px;
}
```