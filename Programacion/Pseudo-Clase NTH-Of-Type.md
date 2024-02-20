---
tags:
  - CSS
aliases:
  - :nth-of-type
links:
  - "[[Pseudo-Clases CSS]]"
---
La pseudo-clase **NTH-OF-Type** permite aplicar estilos a los elementos hermanos que especifiquemos de un contenedor.

Para seleccionar podemos usar distintas formas: *Posición directa*, *Par/Impar*, *Multiplos*.
```css
/*Seleccionamos los elementos hermanos con la clase .item que esten en una posicion que sea multiplo de 3*/
.item:nth-of-type(3n){
	border-color: red;
}
```