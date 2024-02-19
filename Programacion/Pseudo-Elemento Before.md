---
tags:
  - CSS
aliases:
  - ::before
links:
  - "[[Pseudo-Elementos CSS]]"
---
El pseudo-elemento **before** permite añadir contenido visual a los elementos. El **before** se renderiza antes que el elemento.
```css
.item-list::before{
	content: "Hola Mundo";
	color: "red";
}
```