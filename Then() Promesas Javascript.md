---
tags:
  - JavaScript
aliases:
  - then()
links:
  - "[[Promesas Javascript]]"
---
**Then** se ejecuta cuando la promesa pasa de un [[Ciclo de Vida Promesa Javascript|estado]] `pending` a `fulfilled`. Es decir, cuando la [[Promesas Javascript|promesa]] se resuelve con éxito.

```javascript
fetch("https://randomfox.ca/floof/")
.then(response => response.json())
.then(data => console.log(data))
```