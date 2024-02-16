---
tags:
  - CSS
  - Flex
links: "[[CSS]]"
---
La propiedad **Align Self** de [[FlexBox|flex]] es igual que la propiedad [[Flex Align Items|aling items]] con la salvedad que hace efecto en un elemento hijo especifico, por lo que también se debe colocar en ese elemento.

Los tipos de alineaciones que tiene **Aling Items**:
- *start*: Alinea el ítem al inicio del eje secundario.![[Shot - 000040.png]]
- *end*: Alinea el ítem al final del eje secundario.![[Shot - 000041.png]]
- *center*: Alinea los ítems al centro del eje secundario.![[Shot - 000042.png]]
- *strech*: Alinea el ítem *estirándolo* de modo que cubra desde el inicio hasta el final del contenedor.![[Shot - 000043.png]]
- *baseline*: Alinea el ítem en el contenedor según la base del contenido de los ítems del contenedor.![[Shot - 000044.png]]
- *auto*: Hereda el valor de **align-items** del padre (si no se ha definido, es **stretch**).![[Shot - 000043.png]]

```css
.contenedor {
	display: flex;
}
.contenedor-item{
	align-self: start;
}
```