# DIRB

```bash
dirb <"URL Web">
```
# GOBUSTER
## Fuzzing de directorios
```bash
gobuster dir -u <"URL Web"> -w <"Ruta diccionario de rutas web">
```

## Fuzzing de archivos

```bash
gobuster dir -u <"URL Web"> -w <"Ruta diccionario de rutas web"> -x <"Extension de los archivos separadas por coma">
```

# DIRSEARCH
## Fuzzing de directorios automático
```bash
dirsearch -u <"URL Web">
```
## Fuzzing de directorios con diccionario específico
```bash
dirsearch -u <"URL Web"> -w <"Ruta diccionario de rutas web">
```
# WFUZZ
## Fuzzing de directorios
```bash
wfuzz -c --hc=404 -w <"Ruta diccionario de rutas web"> <"URL Web">/FUZZ
```
## Fuzzing de subdominios
```bash
wfuzz -c --hc=404 -w <"Ruta diccionario de subdominios"> -H "Host: FUZZ.<"Dominio">" -u <"IP Victima">
```