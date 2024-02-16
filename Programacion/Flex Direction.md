---
tags:
  - CSS
  - Flex
aliases:
  - flex-direction
  - flex direction
links: "[[CSS]]"
---
La propiedad **Flex Direction** establece la dirección del eje principal. Que tomaran los hijos dentro de un contenedor [[FlexBox|flex]]. Debido a que solo podremos trabajar en un solo eje, lo cual es la principal diferencia con [[Grid]].
![Flex CSS: ¿Cómo funciona?](https://lenguajecss.com/css/maquetacion-y-colocacion/flex/flex-como-funciona.png)

Los tipos de dirección que hay son:
 - *row*: Coloca los elementos en forma de fila.![[Shot - 000017.png]]
 - *row-reverse*: Coloca los elementos en forma de fila invertida.![[Shot - 000018.png]]
 - *column*: Coloca los elementos en forma de columna![[Shot - 000019.png]]
 - *column-reverse*: Coloca los elementos en forma de columna invertida.![[Shot - 000020.png]]
 - *flex*: Coloca los elementos automaticamente en función del resto de propiedades.

Por defecto con [[FlexBox|flex]] el contenedor tiene una dirección *Row*.
```css
.contenedor {
	display: flex;
	flex-direction: row;
}
```
