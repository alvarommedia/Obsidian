---
tags:
  - CSS
aliases:
  - :placeholder-show
links:
  - "[[Pseudo-Clases CSS]]"
---
La pseudo-clase **Not** permite aplicar estilos mientras no se cumpla una determinada condición.
```css
.username:not(:placeholder-show, :focus){
	border-color: red;
}
```