---
tags:
  - CSS
  - Flex
aliases:
  - justify content
  - justify-content
---
La propiedad **Justify Content** de [[FlexBox|flex]] permite alinear los elementos en el eje principal del contendor.

Los tipos de alineaciones que tiene **Justify Content**:
- *start*: Agrupa los ítems al inicio del eje principal.![[Shot - 000011.png]]
- *end*: Agrupa los ítems al final del eje principal.![[Shot - 000012.png]]
- *center*: Agrupa los ítems al centro del eje principal.![[Shot - 000013.png]]
- *space-between*: Distribuye los ítems dejando espacio entre ellos.![[Shot - 000014.png]]
- *space-around*: Distribuye los ítems dejando espacio alrededor de ellos.![[Shot - 000015.png]]
- *space-evenly*: Distribuye como space-around, pero con un espacio exactamente igual alrededor de ellos.![[Shot - 000016.png]]
```css
.contenedor {
	display: flex;
	justify-content: start;
}
```