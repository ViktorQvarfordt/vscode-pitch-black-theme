# VS Code Pitch Black Color Theme

All backgrounds and unnecessary borders are black. Syntax highlighting colors are taken from the [Dark+](https://github.com/Microsoft/vscode/blob/master/extensions/theme-defaults/themes/dark_defaults.json) (default) theme.


## Settings

Some features cannot be enabled automatically by this extension. In the user settings, set the following.

- Black title bar: `"window.titleBarStyle": "custom"`
- Remove highlighting of tab lines etc: `"workbench.colorCustomizations": { "editorWhitespace.foreground": "#000" }`
- Remove line next to scroll bar: `"editor.overviewRulerBorder": false`


## Manual Install

```
cd ~/.vscode/extensions
git clone https://github.com/ViktorQvarfordt/vscode-pitch-black-theme.git pitch-black-theme
```
