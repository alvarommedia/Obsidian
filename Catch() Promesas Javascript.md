---
tags:
  - JavaScript
aliases:
  - catch()
links:
  - "[[Promesas Javascript]]"
---
**Catch** se ejecuta cuando la promesa pasa de un [[Ciclo de Vida Promesa Javascript|estado]] `pending` a `rejected`. Es decir, cuando la [[Promesas Javascript|promesa]] se resuelve con fallo.

```javascript
fetch("https://randomfox.ca/floof/")
.then(response => response.json())
.then(data => console.log(data))
.catch(handleError)
```