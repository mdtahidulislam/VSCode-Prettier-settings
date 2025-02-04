# VSCode Settings
## .vscode/extensions.json
``` json
{
  "recommendations": ["shopify.theme-check-vscode", "esbenp.prettier-vscode"]
}
```
## .vscode/settings.json
``` json
{
  "editor.formatOnSave": false,
  "editor.tabSize": 4,
  "[javascript]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```
# Prettier Settings
## .prettierrc.json
``` json
{
  "printWidth": 120,
  "tabWidth": 4,
  "useTabs": true,
  "trailingComma": "none",
  "arrowParens": "avoid",
  "semi": false
}
```
