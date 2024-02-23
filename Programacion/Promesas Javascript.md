---
tags:
  - JavaScript
aliases:
  - promises
  - promesas
links:
  - "[[Asincronia Javascript]]"
---
Las **Promesas** nos permite realizar una tarea cuando un suceso [[Asincronia Javascript|asincrono]]. Sea exitosa o no.
```javascript
fetch(`https://gutendex.com/books?search=${query}`)
  .then((response) => response.json())
```