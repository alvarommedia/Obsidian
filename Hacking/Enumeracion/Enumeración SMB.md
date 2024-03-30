# SMBCLIENT
## Listar recursos compartidos con usuario anónimo
```bash
smbclient -L //<"IP Victima"> -N
```

## Listar recursos compartidos con credenciales validas
```bash
smbclient -L //<"IP Victima"> -U <"Usuario">
```

## Conectarse a recurso compartido con usuario anónimo
```bash
smbclient -L //<"IP Victima">/<"Recurso"> -N
```

## Conectarse a recurso compartido con credenciales validas
```bash
smbclient -L //<"IP Victima">/<"Recurso"> -U <"Usuario">
```

## Descargar archivo de recurso compartido
# SMBMAP
# Listar permisos en recursos compartidos con usuario anónimo
```bash
smbmap -H <"IP Victima"> 
```
# Listar permisos en recursos compartidos con credenciales validas
```bash
smbmap -H <"IP Victima"> -u <"Usuario"> -p <"Contraseña">