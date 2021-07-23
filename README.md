# VS Code Pitch Black Color Theme  

[![marketplace](https://img.shields.io/visual-studio-marketplace/v/ViktorQvarfordt.vscode-pitch-black-theme?color=brightgreen&label=Visual%20Studio%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)
[![installs](https://img.shields.io/visual-studio-marketplace/i/ViktorQvarfordt.vscode-pitch-black-theme?label=Installs)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)
[![rating](https://img.shields.io/visual-studio-marketplace/r/ViktorQvarfordt.vscode-pitch-black-theme?label=Rating)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)
  
All backgrounds and unnecessary borders are black. Syntax highlighting colors are taken from the [Dark+](https://github.com/Microsoft/vscode/blob/master/extensions/theme-defaults/themes/dark_defaults.json) (default) theme. 

![Screenshot](https://raw.githubusercontent.com/ViktorQvarfordt/vscode-pitch-black-theme/master/screenshot.png)
  
  
## Install and activate  
  
1. Install: `ctrl+p` (or `cmd+p`), enter `ext install pitch black`.  
2. Activate: `ctrl+k, ctrl+t` (or `cmd+k, cmd+t`), select `Pitch Black`.  
  
  
## Settings  
  
Some features cannot be enabled automatically by this extension. In the user settings, set the following.  
  
- Remove highlighting of tab lines etc: `"workbench.colorCustomizations": { "editorWhitespace.foreground": "#000" }`  
- Remove line next to scroll bar: `"editor.overviewRulerBorder": false`  
- Black title bar: `"window.titleBarStyle": "custom"`  
  
  
## Manual Install  
  
```  
cd ~/.vscode/extensions  
git clone https://github.com/ViktorQvarfordt/vscode-pitch-black-theme.git pitch-black-theme  
```
