---
tags:
  - CSS
  - Flex
links: "[[CSS]]"
---
Propiedad de [[FlexBox|flex]] que establece el tamaño base por defecto que tendrán los elementos, antes de aplicarle la distribución de espacio.

Los tipos de Basis que hay son:
- *Content*: El elemento tiene un tamaño ajustado el contenido.
- *Unidades*: El elemento tiene un tamaño ajustado de cualquier unidad de medida.

Por defecto con [[FlexBox|flex]] el contenedor tiene basis es *content*.
```css
.contenedor {
	display: flex;
}
.contenedor-item{
	flex-basis: content;
}
```