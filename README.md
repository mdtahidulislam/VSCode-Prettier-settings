# VSCode-Prettier-settings
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
