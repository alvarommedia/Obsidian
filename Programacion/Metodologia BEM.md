---
tags:
  - CSS
  - Metodologia
aliases:
  - BEM
links: "[[CSS]]"
---
La metodologia **BEM** permite tener un [[CSS]] mas mantenible y reui.

**BEM** consiste en nombrar los [[Selectores CSS|selectores]] de [[Clase HTML|clase]] en función de su intencionalidad. 

Las siglas provienen de la manera de nombrar las [[Clase HTML|clases]]: Block__Element--Modifier. En el bloque añadimos el contexto, en el elemento añadimos el elemento dentro del bloque y como modificador, situaciones especiales en los que se pueda encontrar el elemento.
# ❌Sin usar Bem❌
```css
.card .content .nav_link .actived{

}
```

# ✅Usando Bem✅
```css
.card__link--actived{

}
```