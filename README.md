# Isale Pot Dark VS Code Theme

I grew tired of dark theme and decided to create one customised to my taste. If you're my kind of weirdo, this might interest you.

I don't plan on publishing it yet, as I will not transfer my hell to others. But if you decided to join me here's how to get there

![alt Isale Pot Preview](https://github.com/shonubijerry/true-dark-vscode-theme/blob/main/true-dark-preview.png?raw=true)

## Setup
- Clone this repo

- Install Tools and Visual Studio Code Extension Manager
  ```
  npm install -g vsce yo generator-code
  ```

- Customise the theme `themes/isale-pot-color-theme.json`

- Test your changes
  ```
  code .
  ```
- Press F5 to launch an extension development window with your theme applied. 
  You should see your custom theme in the theme selection menu (Ctrl+K, Ctrl+T).

- Package for installation
  ```
  vsce package
  ```

- Install the Theme Locally:
  ```
  code --install-extension isale-pot-0.0.1.vsix
  ```

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
