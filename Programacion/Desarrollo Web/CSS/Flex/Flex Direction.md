---
tags:
  - CSS
  - Flex
aliases:
  - flex-direction
---
La propiedad **Flex Direction** establece la dirección. Que tomaran los hijos dentro de un contenedor [[Flex]]. Debido a que solo podremos trabajar en un solo eje, lo cual es la principal diferencia con [[Grid]].

Los tipos de dirección que hay son:
 - *row*: Coloca los elementos en forma de fila.
 - *row-reverse*: Coloca los elementos en forma de fila invertida.
 - *column*: Coloca los elementos en forma de columna
 - *column-reverse*: Coloca los elementos en forma de columna invertida.
 - *flex*: Coloca los elementos automaticamente en función del resto de propiedades.

Por defecto con [[flex]] el contenedor tiene una dirección *Row*.
```css
.contenedor {
	display: flex;
	flex-direction: row;
}
```
