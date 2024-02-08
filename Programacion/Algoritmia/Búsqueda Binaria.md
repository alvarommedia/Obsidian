---
tags:
  - Algortimica
---
Permite realizar una búsqueda dentro de un array, de manera optimizada, sin tener que recorrer todos los indices de ese array.

Para ello se segmenta el array por la mitad y se comprueba si el valor a buscar se encuentra en la primera mitad o no.

En la mitad que se encuentre el valor se vuelve a segmentar en dos y se realiza la misma comprobación. Así sucesivamente hasta que se encuentre el elemento o no queden elementos.
# [[JavaScript]]
```javascript
function busquedaBinaria(array, valor){
	 const left = 0
	 const rigth = array.length
	 const middle = Math.floor((left + rigth)/2)
}
```