---
tags:
  - CSS
  - Flex
aliases:
  - align content
  - align-content
---
**Align Content** es un caso particular de [[Flex Align Items|aling items]]. Nos servirá cuando estemos tratando con un contenedor flex *multilinea* creado mediante [[Flex Wrap|flex wrap]]. Nos permitirá alinear las lineas dentro del contenedor.

Los tipos de alineaciones que tiene **Align Content**:
- *start*: Agrupa los ítems al inicio del eje principal.
 ![[Shot - 000030.png]]
- *end*: Agrupa los ítems al final del eje principal.
 ![[Shot - 000031.png]]
- *center*: Agrupa los ítems al centro del eje principal.
![[Shot - 000032.png]]
- *space-between*: Distribuye los ítems desde el inicio hasta el final.
![[Shot - 000036.png]]
- *space-around*: Distribuye los ítems dejando el mismo espacio a los lados de cada uno.
![[Shot - 000034.png]]
- *strech*: Estira los ítems para ocupar de forma equitativa todo el espacio.
![[Shot - 000035.png]]

```css
.contenedor {
	display: flex;
	align-content: start;
}
```