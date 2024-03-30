Si tenemos una shell de meterpreter podemos usar Metasploit par localizar los exploits de la escalada de privilegios a los que la maquina es vulnerable.

```bash
background
```

```bash
search local_exploit_suggester
```

```bash
use 0
```

```bash
sessions -l
```

```bash
set SESSION <"ID de la sesion de meterpreter">
```

```bash
run
```