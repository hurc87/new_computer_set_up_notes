# New Computer Set Up Notes - for windows

## Text Editor

* [VS Code](https://code.visualstudio.com/) - current one I am using both for personal projects and at work, current handy extensions can be found [here](#vs-code-extensions).
* [Atom](https://atom.io/) 

## Git version control

[Git Bash](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

The usual Ctrl+C and Ctrl+V will not work in Git Bash as these are reserved for other functions - Ctrl+C interrupts the currently running command, while Ctrl+V tells the terminal to treat the next typed character as a literal, (e.g. to literally add a keyboard combo such as Ctrl+C). 

To use the keyboard: Hold Shift and use the left/right arrows to select a text area, then press Enter to copy. Paste text by pressing Insert.

To use the mouse: Left-click and drag to highlight a text selecting, then right click to copy. Move the cursor to the desired location and right-click to paste the previously copied text.

## Connect to Github

Connecting to github using a SSH key can be found in their [docs](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh). It will guide you through how to check if you already have a key, how to generate a new one, and how to add this to your github account.

## Installing node 

Install for node can be found [here](https://nodejs.org/en/download/). Try to download the LTS version which tends to be more stable - was told to only download the even versions - not sure how true this actually is?

Usually use nvm at work to switch between the different node versions we use on a project. NVM is only available on mac or linux, however windows have their own version which can be found [here](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-windows). You would need to uninstall node and reinstall using this package - might be something to come back to in the future?

## VS Code Extensions

#### Currently using

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
* [Bracket Colouriser](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
* [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
* [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

#### Not used yet but recommended
* [Rest Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
* [Javascript es6 snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
* [React-Native/React/Redux snippets for es6/es7](https://marketplace.visualstudio.com/items?itemName=EQuimper.react-native-react-redux)
* [React Standard Style code snippets](https://marketplace.visualstudio.com/items?itemName=TimonVS.ReactSnippetsStandard)
* [Todo highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
* [Todo+](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-todo-plus)
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
* [Auto Complete Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag)
