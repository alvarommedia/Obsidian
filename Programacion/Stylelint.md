---
tags:
  - CSS
  - Herramientas
links:
  - "[[Linter]]"
  - "[[CSS]]"
  - "[[NPM]]"
---
**Stylelint** es un linter para [[CSS]], el cual permite mantener un estilo, evitar errores y aplicar buenas practicas.

# Instalar Stylelint en VSCODE para que corrija automaticamente los errores al guardar.

1. Debemos añadir la [extension](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint) de **Stylelint** a VSCode.
2. Añadir la configuración al settings.json:
	```json
"stylelint.validate": ["css", "scss"],

  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,

  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
```

# Instalar en el proyecto los paquetes de Stylelint.
```bash
pnpm i stylelint
```

# Configurar Stylelint
Para configurar **Stylelint** en el proyecto debemos añadir el archivo `.stylelintrc.json` y dentro añadir los [[Plugins StyleLint|plugins]], [[Configuraciones Stylelint|configuraciones]] y [[Reglas Stylelint|reglas]].
