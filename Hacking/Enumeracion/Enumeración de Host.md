# Enumerar puertos

## NMAP

### Enumerar todos los puertos TCP abiertos una una maquina (CTF)

```bash
nmap -p- --open -sS --min-rate 2000 -n -Pn <"IP"> -oG escaneo_puertos
```

### Enumerar todos los puertos TCP abiertos una una maquina

```bash
nmap -p- --open -sS -T0 -n -Pn <"IP"> -oG escaneo_puertos
```

### Enumerar todos los puertos UDP abiertos una una maquina (CTF)

```bash
nmap -p- --open -sU --min-rate 2000 -n -Pn <"IP"> -oG escaneo_puertos_UDP
```

### Enumerar todos los puertos TCP abiertos una una maquina

```bash
nmap -p- --open -sU -T0 -n -Pn <"IP"> -oG escaneo_puertos_UDP
```