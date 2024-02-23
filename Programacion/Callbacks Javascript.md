---
tags:
  - JavaScript
aliases:
  - callbacks
links:
  - "[[Asincronia Javascript]]"
---
Los **Callbacks** son [[Funciones Javascript|funciones]] que se pasan como parametro de otras [[Funciones Javascript|funciones]].
```javascript
app.get("/", (req, res) => {
	res.send("Hello from a callback!");
});
```
