---
tags:
  - Algortimica
---
Permite realizar una búsqueda dentro de un array, de manera optimizada, sin tener que recorrer todos los indices de ese array.

Para ello se segmenta el array por la mitad y se comprueba si el valor a buscar se encuentra en la primera mitad o no.

En la mitad que se encuentre el valor se vuelve a segmentar en dos y se realiza la misma comprobación. Así sucesivamente hasta que se encuentre el elemento o no queden elementos.

Una vez encontrado se devuelve el indice.
# [[JavaScript]]
```javascript
//Funcion Iterativa
function busquedaBinaria(array, valor){
	 let left = 0
	 let rigth = array.length

	 while (left <= rigth){
		 const middle = Math.floor((left + rigth)/2)	 
		 if (array[middle] === valor) middle
		 if (array[middle] < valor){
			 left = middle + 1
		 } else {
			 rigth = middle - 1
		 }
	 }
}
```
```javascript
//Funcion Recursiva
function busquedaBinaria(array, valor){
	 if(array.length <= 0) return -1
	 const left = 0
	 const rigth = array.length
	 const middle = Math.floor((left + rigth)/2)
	 
	 if(array.length <= 0) return -1
	 if(array[middle] === valor) return middle
	 
}
```