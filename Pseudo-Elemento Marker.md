---
tags:
  - CSS
aliases:
  - ::marker
links:
  - "[[CSS]]"
  - "[[Pseudo-Elementos]]"
---
El pseudo-elemento **marker** permite aplicar estilos a el decorador de un [[Li HTML|item de lista]].
```css
.item-list::marker{
	content: "^";
	font-size: 1.5rem;
}
```