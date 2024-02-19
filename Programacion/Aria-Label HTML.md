---
tags:
  - HTML
aliases:
  - aria-label
links:
  - "[[Input HTML]]"
  - "[[Accesibilidad]]"
  - "[[Atributos HTML]]"
---
El atributo *Aria-Label* en los [[Input HTML|input]] permite añadir una un [[Label HTML|label]] el cual no se renderiza gafricamente, pero si que será leído por lo [[Lector de Pantalla|lectores de pantalla]]
```html
<input type="text" 
	   aria-label="Nombre y apellidos" 
	   name="nombre-apellidos" 
	   placeholder="Nombre y Apellidos"
/>
```