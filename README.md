# VSCode px to vh converter

This is an extension for Visual Studio Code that allows you to convert px to vh, and vice versa.
Forked from px-to-rem

## Usage

### Keybindings

- `Alt+Z` Px to vh, and vh to px. Converts selected text from px to vh, and vh to px.
- `Alt+S` Asks for a new viewport height value.

![](./imgs/alt_z.gif)

### Commands

- Px to vh, and vh to px. Converts selected text from px to vh, and vh to px.
- Px to vh. Converts selected text from px to vh
- vh to px. Converts selected text from vh to px
- Change px viewport height. Asks for a new viewport height value.

## Extension Settings

This extension contributes the following settings:

- `px-to-vh.viewport-height`: height of the viewport the pixels set to. Default is 1080px.
- `px-to-vh.number-of-decimals-digits`: maximum number of decimals digits a px or vh can have
- `px-to-vh.only-change-first-ocurrence`: set to change all or only the first selected ocurrence of px/vh
- `px-to-vh.notify-if-no-changes`: enable/disable notification that alerts the users if no conversion could be made

## Known Issues

- If you select a value with multiple cursors it will get converted, but following cursors may change place after the conversion.
- '_Edits from command extension.pxTovhAndVhToPx were not applied_' message appears in debug console.

---

## Contributing

Feel free to fork this or the original repository and use it the way you like. If you want to propose a nice new feature, just create a pull request from your forked branch.
[original repo (px-to-rem)](https://github.com/sainoba/vscode-px-to-rem)

**Enjoy!**
