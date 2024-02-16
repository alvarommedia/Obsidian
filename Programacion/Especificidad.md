---
tags:
  - CSS
  - Selectores
links: "[[CSS]]"
---
La **Especificidad** hace referencia a que tan unico es un [[Selectores CSS|selector]] en [[CSS]]. Cuanto mas especifico es un [[Selectores CSS|selectores]] menos reutilizable es y a su vez hace menos escalable en las situaciones en las que se necesita tener un [[Selectores CSS|selector]] mas especifico.
# Como se mide la especificidad
Para medirla, se emplea una escala numerica dividida en bloques que suma uno en cada tipo de [[selector]] en el bloque que afecte.

Los bloque cuanto mas a la derecha añaden mas especifidad. Cada bloque no tiene un limite de especificidad. La especificidad mas baja de cada bloque es 0
![[Shot - 000062.png]]

