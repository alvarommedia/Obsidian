Saber los binarios que se ejecutan automáticamente como sudo. Es interesante saber cuáles son por si alguno fuese vulnerable.

```bash
find / -perm 4000 2>/dev/null
```

Posteriormente, podemos usar la web https://gtfobins.github.io/ para saber como escalar privilegios con esos binarios.