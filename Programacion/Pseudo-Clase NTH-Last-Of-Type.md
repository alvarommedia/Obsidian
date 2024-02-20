---
tags:
  - CSS
aliases:
  - :nth-last-of-type
links:
  - "[[Pseudo-Clases CSS]]"
---

La pseudo-clase **NTH-Last-OF-Type** permite aplicar estilos a los elementos hermanos que especifiquemos de un contenedor, empezando a contar desde el ultimo elemento.
```css
/*Seleccionamos los elementos hermanos con la clase .item que esten en una posicion que sea multiplo de 3. Empezando a contar desde el ultimo elemento*/
.item:nth-last-of-type(3n){
	border-color: red;
}
```