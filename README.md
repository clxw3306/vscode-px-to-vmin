# VSCode px to vmin converter

This is an extension for Visual Studio Code that allows you to convert px to vmin, and vice versa.
Forked from px-to-rem

## Usage

### Keybindings

- `Alt+Z` Px to vmin, and vmin to px. Converts selected text from px to vmin, and vmin to px.
- `Alt+S` Asks for a new viewport height value.

![](./imgs/alt_z.gif)

### Commands

- Px to vmin, and vmin to px. Converts selected text from px to vmin, and vmin to px.
- Px to vmin. Converts selected text from px to vmin
- vmin to px. Converts selected text from vmin to px
- Change px viewport height. Asks for a new viewport height value.

## Extension Settings

This extension contributes the following settings:

- `px-to-vmin.viewport-height`: height of the viewport the pixels set to. Default is 1080px.
- `px-to-vmin.number-of-decimals-digits`: maximum number of decimals digits a px or vmin can have
- `px-to-vmin.only-change-first-ocurrence`: set to change all or only the first selected ocurrence of px/vmin
- `px-to-vmin.notify-if-no-changes`: enable/disable notification that alerts the users if no conversion could be made

## Known Issues

- If you select a value with multiple cursors it will get converted, but following cursors may change place after the conversion.
- '_Edits from command extension.pxTovminAndvminToPx were not applied_' message appears in debug console.

---

## Contributing

Feel free to fork this or the original repository and use it the way you like. If you want to propose a nice new feature, just create a pull request from your forked branch.
[original repo (px-to-rem)](https://github.com/sainoba/vscode-px-to-rem)

**Enjoy!**
