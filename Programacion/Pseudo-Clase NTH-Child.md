---
tags:
  - CSS
aliases:
  - :nth-child
links:
  - "[[Pseudo-Clases CSS]]"
---
La pseudo-clase **NTH-Child** permite aplicar estilos a los hijos que especifiquemos de un contenedor.

Para seleccionar podemos usar distintas formas: *Posición directa*, *Par/Impar*, *Multiplos*
```css
/*Seleccionamos los elementos hijo que esten en una posicion que sea multiplo de 3*/
.contenedor:nth-child(3n){
	border-color: red;
}
```