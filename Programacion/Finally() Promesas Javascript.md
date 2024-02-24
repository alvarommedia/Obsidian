---
tags:
  - JavaScript
aliases:
  - finally()
links:
  - "[[Promesas Javascript]]"
---
**Finally** se ejecuta cuando la promesa pasa de un [[Ciclo de Vida Promesa Javascript|estado]] `pending` a `settled` Es decir, cuando la [[Promesas Javascript|promesa]] se resuelve, independientemente si es con fallo o con exito.

```javascript
fetch("https://randomfox.ca/floof/")
.then(response => response.json())
.then(data => console.log(data))
.catch(handleError)
.finally(console.log("Fetch Finalizado"))
```