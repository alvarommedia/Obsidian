---
tags:
  - CSS
  - Flex
aliases:
  - flex-wrap
---
**Flex Wrap** es una propiedad de [[Flex|flex]] que determina el comportamiento del contenido hijo en el caso de desbordamiento.

Los tipos de wrap que hay son:
- *nowrap*: Evita que el contenido que tenga desbordamiento salte a una linea inferior.
- *wrap*: Fuerza que el contenido que tenga desbordamiento salte a una linea inferior.
- *wrap-reverse*: Fuerza que el contenido que tenga desbordamiento salte a una linea inferior de manera inversa.

Por defecto con [[flex]] el contenedor tiene un wrap de *nowrap*.
```css
.contenedor {
	display: flex;
	flex-wrap: nowrap;
}
```