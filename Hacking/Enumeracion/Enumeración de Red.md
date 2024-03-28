# Reconocimiento de Hosts en la Red

## ARP SCAN

```bash
arp-scan -i <"INTERFAZ DE RED"> --localnet
```

## Net Discover

```bash
netdiscover -i <"INTERFAZ DE RED"> -r <"CIDR DE LA RED"> 
```

## NMAP

```bash
nmap -sn <"CIDR DE LA RED"> 
```

> Como truco, se puede usar una subred en el CIDR de una clase superior, para descubrir equipos en otras redes, en caso de que no haya segmentación