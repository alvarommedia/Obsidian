---
tags:
  - JavaScript
aliases:
  - reject
links:
  - "[[Promesas Javascript]]"
---
*Reject* permite cancelar la ejecución de una promesa, devolviendo un error. Povocando que se ejecute el [[Catch() Promesas Javascript|catch()]]
```javascript
export function getBooksFromApi(search) {
	return new Promise((resolve, reject) => {
		fetch(`https://gutendex.com/books?search=${search}`)
			.then((response) => response.json())
			.then((data) => {
				if (data.count === 0) {
					reject("El libro no existe");
				}
				resolve(data.results);
			});
	});
}
```