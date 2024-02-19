---
tags:
  - CSS
  - Selectores
links: []
---
Los errores mas comunes a la hora de utilizar los [[Selectores CSS|selectores]] en son:
# Utilizar [[Selectores CSS|Selectores]] Tag para etiquetas [[HTML 5]] poco utilizadas.
Utilizar etiquetas que se utilizan poco en el [[HTML 5]] y darle estilos específicos a ese elemento.

```css
h1{
	color: red;
	height: 100px;
	width: 100px;
	margin-left: 20px;
}
```

# Sobre especificar los [[Selectores CSS|selectores]].
Añadir especificad en selectores que no lo necesitan, en los que usando un [[Selectores CSS|selectores]] menos especifico el estilo se aplica igualmente.
```html
<article class="card"></article>
```

```css
article .card{
	color: red;
	height: 100px;
	width: 100px;
	margin-left: 20px;
}
```

# Anidamiento excesivo de classes
Anidar excesivamente los [[Selectores CSS|selectores]] para un hijo especifico dentro de otro elemento. Haciendo que si ese mismo elemento esta fuera del padre en otro lugar de la pagina, los estilos no se aplicaran.
```html
<article class="card">
	<img class="image" src="patata" />
</article>
```

```css
.card .img{
	height: 100px;
	width: 100px;
	margin-left: 20px;
}
```
# Componer clases con [[Selectores CSS|selectores]] tag para especificar estilos.
Es la suma de los errores indicados anteriormente: Sobre especificar, utilizar tag, etc.
```html
<article class="card" id="courseClass">
	<img class="image" src="patata" />
	<section></section>
</article>
```

```css
#courseClass section{
	height: 100px;
	width: 100px;
	margin-left: 20px;
}
```
