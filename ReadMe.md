## Settings

```
{
  "editor.fontSize": 13,
  "editor.snippetSuggestions": "top",
  "editor.minimap.enabled": false,
  "editor.linkedEditing": true,
  "editor.tabSize": 2,
  "workbench.iconTheme": "vscode-icons",
  "fontshortcuts.defaultFontSize": 13,
  "fontshortcuts.defaultTerminalFontSize": 13,
	"fontshortcuts.step": 1,
	"editor.lineHeight": 0
}

```

## Extensions packege names for easy install

```
dbaeumer.vscode-eslint
dsznajder.es7-react-js-snippets
esbenp.prettier-vscode
fosshaas.fontsize-shortcuts
quicktype.quicktype
rangav.vscode-thunder-client
streetsidesoftwae.code-spell-checker
vscode-icons-team.vscode-icons
vunguyentuan.vscode-postcss
yoavbis.pretty-ts-errors
```

Open terminal
```
nano vs-extensions.txt
```

Cope entire file names and install all extensions in one line

```
cat vs-extensions.txt | xargs -L1 code --install-extension
```
