---
tags:
  - CSS
  - Flex
---

La propiedad **Flex Order** es otra de las pocas propiedades que se colocan en el hijo de un contenedor de tipo [[FlexBox|flex]]. La cual permite establecer el orden en el que aparecen los elementos en el contenedor.

Por defecto, todos los elementos hijos de un contenedor flex tienen establecido un *order* por defecto al valor `0`, aunque no se especifique de forma explícita. Si indicamos una propiedad *order* con un valor numérico diferente, irá recolocando los ítems según dicho número, colocando antes los elementos con un número *order* más pequeño (_incluso valores negativos_) y después los elementos con números más altos.

```css
.contenedor {
	display: flex;
}
.contenedor-item{
	order: -1;
}
```
