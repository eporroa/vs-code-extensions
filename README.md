# vs-code-extensions
Curated list for VisualStudio Code extensions

## WebDev
``` zsh
code --install-extension 2gua.rainbow-brackets
code --install-extension aaron-bond.better-comments
code --install-extension anseki.vscode-color
code --install-extension dbaeumer.vscode-eslint
code --install-extension CoenraadS.bracket-pair-colorizer
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension cssho.vscode-svgviewer
code --install-extension vscode-icons-team.vscode-icons
code --install-extension HookyQR.beautify
code --install-extension Gruntfuggly.todo-tree
code --install-extension esbenp.prettier-vscode
code --install-extension eamodio.gitlens
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension EditorConfig.EditorConfig
code --install-extension humao.rest-client
code --install-extension jpoissonnier.vscode-styled-components
code --install-extension mechatroner.rainbow-csv
code --install-extension mikestead.dotenv
code --install-extension mrmlnc.vscode-scss
code --install-extension oderwat.indent-rainbow
code --install-extension ryu1kn.partial-diff
code --install-extension shinnn.stylelint
```

## JS
``` zsh
code --install-extension cmstead.jsrefactor
code --install-extension xabikos.JavaScriptSnippets
```

## TS
``` zsh
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension dskwrk.vscode-generate-getter-setter
```

## Node
``` zsh
code --install-extension christian-kohler.npm-intellisense
code --install-extension christian-kohler.path-intellisense
```

## Vue
``` zsh
code --install-extension hollowtree.vue-snippets
code --install-extension octref.vetur
```

## React
``` zsh
code --install-extension jawandarajbir.react-vscode-extension-pack
code --install-extension msjsdiag.vscode-react-native
```

## NG
``` zsh
code --install-extension Angular.ng-template
code --install-extension Mikael.Angular-BeastCode
```

# How to get the extension list
As I read in this [stackoverflow thread](https://stackoverflow.com/questions/35773299/how-can-you-export-vs-code-extension-list):
```
# UNIX:
code --list-extensions | xargs -L 1 echo code --install-extension


# Windows (PowerShell, e. g. using VSCode's integrated Terminal):
code --list-extensions | % { "code --install-extension $_" }
```

# How to import the extension list
```
# UNIX
cat vscode-extension-list.txt | xargs -L 1 code --install-extension
```
