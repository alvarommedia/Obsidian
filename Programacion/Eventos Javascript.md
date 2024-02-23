---
tags:
  - JavaScript
aliases:
  - eventos
  - events
links:
  - "[[Asincronia Javascript]]"
---
Los **Eventos** nos permiten responder a eventos de un determinado tipo que suceden durante la ejecución de nuestro código.
```javascript
button.addEventListener("click", (ev) => {
	const itemId = ev.target.dataset.itemid;

	document.dispatchEvent(new CustomEvent("itemAdded", { detail: { item: itemId } }));
});
```