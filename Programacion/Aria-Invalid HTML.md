---
tags:
  - HTML
aliases:
  - aria-invalid
links:
  - "[[Accesibilidad]]"
  - "[[Input HTML]]"
  - "[[Atributos HTML]]"
---
El atributo *Aria-Invalid* en los [[Input HTML|input]] permite indicar a los [[Lector de Pantalla|lectores de pantalla]] cuando el contenido es invalido.

Para modificar el estado, es necesario [[JavaScript]]
```html
<input type="text" 
	   aria-label="Nombre y apellidos" 
	   name="nombre-apellidos" 
	   placeholder="Nombre y Apellidos"
	   aria-describedby="onlyTextError"
	   aria-invalid
/>
<div id=onlyTextError>
	<p>Introduce solo letrar en el campo</p>
</div>
```