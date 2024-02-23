---
tags:
  - JavaScript
aliases:
  - callback hell
links:
  - "[[Callbacks Javascript]]"
---
Es conocido como **Callback Hell** el problema que surge cuando encadenamos muchos [[Callbacks Javascript|callbacks]], uno dentro de otro. Este problema hace que el código no se legible y que cueste su mantenimiento.

```javascript
writeFile(file, "", () => {
    getUsersFromApi((users) => {
        appendFile(file, JSON.stringify(users), () => {
            copyFile(file, "../dest.json", () => {
                unlink(file, () => {
                    console.log("Process finished!");
                });
            });
        });
    });
});
```

Una solución a este problema serian las [[Promesas Javascript|promesas]]:
```javascript
writeFilePromisified(file, "")
	.then(getUsersFromApi)
	.then((users) => {
		return appendFile(file, JSON.stringify(users));
	})
	.then(() => {
		return copyFile(file, "../dest.json");
	})
	.then(() => {
		return unlink(file);
	})
	.then(() => console.log("Process finished!"));
```

Una solución a este problema seria [[Async-Await]]:
```javascript
await writeFilePromisified(file, "");
const users = await getUsersFromApi();
await appendFile(file, JSON.stringify(users));
await copyFile(file, "../dest.json");
await unlink(file);
console.log("Process finished!");
```