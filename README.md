# [VS Code Pitch Black Color Theme](https://marketplace.visualstudio.com/items?itemName=viktorqvarfordt.vscode-pitch-black-theme)

[![marketplace](https://img.shields.io/visual-studio-marketplace/v/ViktorQvarfordt.vscode-pitch-black-theme?color=brightgreen&label=Visual%20Studio%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)
[![installs](https://img.shields.io/visual-studio-marketplace/i/ViktorQvarfordt.vscode-pitch-black-theme?label=Installs)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)
[![rating](https://img.shields.io/visual-studio-marketplace/r/ViktorQvarfordt.vscode-pitch-black-theme?label=Rating)](https://marketplace.visualstudio.com/items?itemName=ViktorQvarfordt.vscode-pitch-black-theme)

All backgrounds and unnecessary borders are black. Syntax highlighting colors are taken from the [Dark+](https://github.com/Microsoft/vscode/blob/master/extensions/theme-defaults/themes/dark_defaults.json) (default) theme.

![Screenshot](https://raw.githubusercontent.com/ViktorQvarfordt/vscode-pitch-black-theme/master/screenshot.png)


## Install

Follow the instructions at the [marketplace](https://marketplace.visualstudio.com/items?itemName=viktorqvarfordt.vscode-pitch-black-theme) or install directly from the editor:

Press `Ctrl+Shift+P` (or `Cmd+Shift+P`), select `Extensions: Install Extensions`, search for `Pitch Black Theme`.


## Activate

Press `Ctrl+Shift+P` (or `Cmd+Shift+P`), select `Preferences: Color Theme`, select `Pitch Black`.


## Settings

Some features cannot be enabled automatically by a color them. So you should configure it manually in the user settings.

Open the user settings: Press `Ctrl+Shift+P` (or `Cmd+Shift+P`), select `Preferences: Open Settings (JSON)`. Add this into the settings file:

```
  /*
   * Tweak colors to match Pitch Black color theme
   */

  // Black title bar: Allow the title bar to be styled by the color theme
  "window.titleBarStyle": "custom",
  // Hide border next to scroll bar
  "editor.overviewRulerBorder": false,

  // Optional - Make it even darker
  "workbench.colorCustomizations": {
    // Hide editor group borders
    "editorGroup.border": "#000",
    // Hide sidebar border
    "sideBar.border": "#000",
    // Hide indent lines
    "editorWhitespace.foreground": "#000"
  },
```


## Advanced: Manual Install: Useful for developing and testing the theme

```
cd ~/.vscode/extensions
git clone https://github.com/ViktorQvarfordt/vscode-pitch-black-theme.git
```
