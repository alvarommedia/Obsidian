---
tags:
  - CSS
aliases:
  - ::marker
links:
  - "[[Pseudo-Elementos]]"
---
El pseudo-elemento **marker** permite aplicar estilos a el decorador de un [[LI HTML|item de lista]].
```css
.item-list::marker{
	content: "^";
	font-size: 1.5rem;
}
```