---
tags:
  - CSS
aliases:
  - :has
links:
  - "[[Pseudo-Clases CSS]]"
---
La pseudo-clase **Has** permite aplicar estilos a los elementos hijo que posean cierto atributo especifico.
```css
form:has(input[type="checkbox"]){
	border-color: red;
}
```