# Enumerar puertos

## NMAP

### Enumerar todos los puertos TCP abiertos una una maquina (CTF)

```bash
nmap -p- --open -sS --min-rate 2000 -n -Pn <"IP"> -oG openPorts -vvv
```

### Enumerar todos los puertos TCP abiertos una una maquina

```bash
nmap -p- --open -sS -T0 -n -Pn <"IP"> -oG openPorts -vvv
```

### Enumerar todos los puertos UDP abiertos una una maquina (CTF)

```bash
nmap -p- --open -sU --min-rate 2000 -n -Pn <"IP"> -oG openPorts_UDP -vvv
```

### Enumerar todos los puertos TCP abiertos una una maquina

```bash
nmap -p- --open -sU -T0 -n -Pn <"IP"> -oG openPorts_UDP -vvv
```

# Enumerar servicios

## NMAP

### Enumerar los servicios que corren en los puertos que se encuentran abiertos

```bash
nmap -sCV -p<"Puertos Abiertos"> <"IP Victima"> -oN scanServices -vvv
```