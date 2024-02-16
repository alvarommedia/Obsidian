---
tags:
  - CSS
  - Flex
aliases:
  - aling items
  - aling-items
links: "[[CSS]]"
---
La propiedad **Align Items** de [[FlexBox|flex]] permite alinear los elementos en el eje secundarios del contenedor.

Los tipos de alineaciones que tiene **Align Items**:
- *start*: Agrupa los ítems al inicio del eje secundario.![[Shot - 000024.png]]
- *end*: Agrupa los ítems al final del eje secundario.![[Shot - 000025.png]]
- *center*: Agrupa los ítems al centro del eje secundario.![[Shot - 000026.png]]
- *strech*: Alinea los ítems *estirándolos* de modo que cubran desde el inicio hasta el final del contenedor.![[Shot - 000027.png]]
- *baseline*: Alinea los ítems en el contenedor según la base del contenido de los ítems del contenedor.![[Shot - 000028.png]]
```css
.contenedor {
	display: flex;
	align-items: start;
}
```