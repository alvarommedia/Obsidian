---
tags:
  - CSS
  - Flex
links: []
---
La propiedad **Flex Shrink** de [[FlexBox|flex]] indica el factor de decrecimiento del cada elemento.

Los tipos de **Shrink** que hay son:
- *0*: El elemento no crece.
- *1*: El elemento crece hasta que la suma se los elementos hijos del contenedor sume el 100% del ancho del contenedor.

Por defecto con [[FlexBox]] el contenedor tiene una **shrink** de *0*.
```css
.contenedor {
	display: flex;
}
.contenedor-item{
	flex-shrink: 0;
}
```