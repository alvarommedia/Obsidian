---
tags:
  - CSS
  - Flex
aliases:
  - flex-wrap
  - flex wrap
links: "[[CSS]]"
---
**Flex Wrap** es una propiedad de [[FlexBox|flex]] que determina el comportamiento del contenido hijo en el caso de desbordamiento.

Los tipos de wrap que hay son:
- *nowrap*: Evita que el contenido que tenga desbordamiento salte a una linea inferior.
 ![[Shot - 000021.png]]
- *wrap*: Fuerza que el contenido que tenga desbordamiento salte a una linea inferior.
![[Shot - 000022.png]]
- *wrap-reverse*: Fuerza que el contenido que tenga desbordamiento salte a una linea inferior de manera inversa.
![[Shot - 000023.png]]

Por defecto con [[FlexBox]] el contenedor tiene un wrap de *nowrap*.
```css
.contenedor {
	display: flex;
	flex-wrap: nowrap;
}
```