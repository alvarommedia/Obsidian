---
tags:
  - JavaScript
aliases:
  - Estados promesa
links:
  - "[[Promesas Javascript]]"
---

# Los Estados de una Promesa:
- *Pending*: Estado inicial, no se ha cumplido ni se ha rechazado.
- *Fulfilled*: La operación se ha completado con éxito.
- *Rejected*: La operación ha fallado.
- *Settled*: Sería el estado que engloba `fulfilled` y `rejected`, es decir, cuando la promesa ya no está `pending`

# Ciclo de vida de una Promesa
![Promesa](https://es.javascript.info/article/promise-basics/promise-resolve-reject.svg)