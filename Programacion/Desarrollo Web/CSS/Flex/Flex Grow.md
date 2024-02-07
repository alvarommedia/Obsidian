---
tags:
  - CSS
  - Flex
---
Propiedad de [[Flex|flex]] que establece si un hijo puede crecer para ajustarse al contenido. Esta propiedad se coloca en los elementos hijo de [[Flex|flex]].

Los tipos de grow que hay son:
- *0*: El elemento no crece.
- *1*: El elemento no crece.

Por defecto con [[flex]] el contenedor tiene una grow de *0*.
```css
.contenedor {
	display: flex;
}
.contenedor-item{
	flex-grow: 0;
}
```