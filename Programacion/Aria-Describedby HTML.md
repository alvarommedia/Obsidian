---
tags:
  - HTML
aliases:
  - aria-describedby
links:
  - "[[Input HTML]]"
  - "[[Accesibilidad]]"
  - "[[Atributos HTML]]"
---
El atributo *Aria-Describedby* en los [[Input HTML|input]] permite vincular el error que parece en caso de el contenido sea incorrecto, y en caso de que el [[Aria-Invalid HTML|aria-invalid]] sea true. Los [[Lector de Pantalla|lectores de pantalla]] sean conscientes del error.
```html
<input type="text" 
	   aria-label="Nombre y apellidos" 
	   name="nombre-apellidos" 
	   placeholder="Nombre y Apellidos"
	   aria-describedby="onlyTextError"
/>
<div id=onlyTextError>
	<p>Introduce solo letrar en el campo</p>
</div>
```