# Hello ! <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">

## A small setup page to show you my settings in VS Code and Terminal for Mac.

## Summary

1. [VS Code](#VS-Code)
2. [Terminal](#Terminal)

## VS Code

### Font: [Fira Code](https://github.com/tonsky/FiraCode)

> Fira Code is a free monospaced font containing ligatures for common programming multi-character combinations. This is just a font rendering feature: underlying code remains ASCII-compatible. This helps to read and understand code faster. For some frequent sequences like .. or //, ligatures allow us to correct spacing.
>
> **Fira Code**

You can download it from [here](https://github.com/tonsky/FiraCode/wiki/Installing)
To use it in `VS Code`, follow [these explanations](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions)

**TL;DR**:
Add this to your VS Code `settings.JSON`:

```JSON
"editor.fontFamily": "Fira Code",
"editor.fontLigatures": true,
```
### Extensions

- beautify
- bracket
- vs code browser preview
- cobalt 2
- debugger for Chrome
- git extension pack
- git history
- git lens
- vs html css
- html snippets
- javascript snippets
- liveserver
- prettier
- project manager
- vscode icons
- web validator

### Settings

Here are my VS Code Settings.
Please only copy the line you understand and want to use.

```JSON

{
    "editor.renderControlCharacters": true,
    "workbench.colorTheme": "Cobalt2",
    "editor.fontSize": 14,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "git.enableSmartCommit": true,
    "workbench.iconTheme": "vscode-icons",
    "liveServer.settings.CustomBrowser": "chrome",
    "vsicons.dontShowNewVersionMessage": true,
    "files.autoSave": "afterDelay",
    "debug.javascript.autoAttachFilter": "smart",
    "git.autofetch": true,
    "vscode-w3cvalidation.validator-token": "Thu, 01 Jan 1970 00:00:00 GMT",
    "editor.accessibilityPageSize": 6,
    "editor.cursorBlinking": "expand",
    "editor.cursorStyle": "line",
    "files.trimFinalNewlines": true,
    "editor.mouseWheelZoom": true,
    "editor.letterSpacing": 0.2,
    "editor.lineHeight": 20,
    "[json]": {
        "editor.quickSuggestions": {
            "strings": true
        },
        "editor.suggest.insertMode": "replace",
        "gitlens.codeLens.scopes": [
            "document"
        ]
    },
    "liveServer.settings.donotShowInfoMsg": true,
    "liveServer.settings.showOnStatusbar": true,
    "[javascript]": {  
        "editor.fontLigatures": "'ss02', 'ss19'",
    },
    "[html]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    "[css]": {
        "editor.defaultFormatter": "HookyQR.beautify"
    },
    

}
```

## Terminal:

Terminal for mac


### Framework: [Oh My Zsh](https://ohmyz.sh)

> Oh My Zsh will not make you a 10x developer...but you may feel like one!
>
> **Oh My Zsh**

An awesome shell with autocompletion, history, alias, plugins, etc.

Install it by running: `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
