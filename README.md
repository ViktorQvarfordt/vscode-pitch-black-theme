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

## Enable additional darkness

Some features cannot be enabled automatically by a color them. So you should configure it manually in the user settings.

Open the user settings: Press `Ctrl+Shift+P` (or `Cmd+Shift+P`), select `Preferences: Open Settings (JSON)`. Add this into the settings file:

```json
{
  // Pitch black - Title bar (Allow the title bar to be styled by the color theme)
  "window.titleBarStyle": "custom",
  // Pitch plack - Hide border next to scroll bar that separates panes
  "editor.overviewRulerBorder": false,
}
```

## Optional settings - Configure some colors manually

If you like the theme as it is, you don't need to read this.

This color theme removes many lines and borders by default, if you want you can add them back:

```json
{
  // Optional - Bring back some lines and borders
  "workbench.colorCustomizations": {
    "sideBar.border": "#222",
    "editorGroup.border": "#222",
    "editorIndentGuide.background": "#222", // Indent lines
    "editorIndentGuide.activeBackground": "#333", // Active indent line
  }
}
```

If you don't like the text selection and search highlight colors you can configure them:
```json
{
  "workbench.colorCustomizations": {
    // Text selection
    "editor.selectionBackground": "#007acc",
    "editor.selectionHighlightBackground": "#007acc",
    "editor.inactiveSelectionBackground": "#007acc",

    // Find results
    "editor.findMatchBackground": "#fa05",
    "editor.findMatchHighlightBackground": "#fa05",
    "editor.findMatchBorder": "#fe0",
    "editor.findMatchHighlightBorder": "#fe0",
    "editor.selectionHighlightBorder": "#fe0",
  }
}
```

## Advanced: Manual Install: Useful for developing and testing the theme

```
cd ~/.vscode/extensions
git clone https://github.com/ViktorQvarfordt/vscode-pitch-black-theme.git
```
