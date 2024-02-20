---
tags:
  - CSS
aliases:
  - :is
links:
  - "[[Pseudo-Clases CSS]]"
---
La pseudo-clase **Is** permite aplicar estilos a los elementos que sean del tipo que se especifica. En caso de haber mas de uno, se aplicara si coinciden con uno de ellos.
```css
:is(article, aside, section){
	border-color: red;
}
```