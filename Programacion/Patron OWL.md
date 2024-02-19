---
tags:
  - CSS
aliases:
  - owl
  - patron owl
links:
  - "[[Patrones de Selectores]]"
---
El **Patron OWL** permite dar seleccionar los elementos que tengan dentro del mismo padre, que sean precedidos por un hermano.
```css
* + *{
	margin-top: 1rem;
}
```