---
tags:
  - CSS
aliases:
  - ::after
links:
  - "[[Pseudo-Elementos]]"
---
El pseudo-elemento **after** permite añadir contenido visual a los elementos. El **after** se renderiza despues que el elemento.

🚨IMPORTANTE NO AÑADIR CONTENIDO RELEVANTE, PARA LOS LECTORES DE TEXTO ES INVISIBLE🚨
```css
.item-list::after{
	content: "Hola Mundo";
	color: "red";
}
```