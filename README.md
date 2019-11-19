# vs-code-extensions
Curated list for VisualStudio Code extensions

## #WebDev
[`code --install-extension 2gua.rainbow-brackets`](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
[`code --install-extension aaron-bond.better-comments`](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
[`code --install-extension anseki.vscode-color`](https://marketplace.visualstudio.com/items?itemName=anseki.vscode-color)
[`code --install-extension dbaeumer.vscode-eslint`](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
[`code --install-extension CoenraadS.bracket-pair-colorizer`](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
[`code --install-extension CoenraadS.bracket-pair-colorizer-2`](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
[`code --install-extension cssho.vscode-svgviewer`](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
[`code --install-extension vscode-icons-team.vscode-icons`](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
[`code --install-extension HookyQR.beautify`](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
[`code --install-extension Gruntfuggly.todo-tree`](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
[`code --install-extension esbenp.prettier-vscode`](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
[`code --install-extension eamodio.gitlens`](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
[`code --install-extension msjsdiag.debugger-for-chrome`](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
[`code --install-extension EditorConfig.EditorConfig`](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
[`code --install-extension humao.rest-client`](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
[`code --install-extension jpoissonnier.vscode-styled-components`](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
[`code --install-extension mechatroner.rainbow-csv`](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
[`code --install-extension mikestead.dotenv`](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
[`code --install-extension mrmlnc.vscode-scss`](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss)
[`code --install-extension oderwat.indent-rainbow`](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
[`code --install-extension ryu1kn.partial-diff`](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff)
[`code --install-extension shinnn.stylelint`](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)


## #JavaScript

[`code --install-extension cmstead.jsrefactor`](https://marketplace.visualstudio.com/items?itemName=cmstead.jsrefactor)
[`code --install-extension xabikos.JavaScriptSnippets`](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)


## ##TypeScript

[`code --install-extension ms-vscode.vscode-typescript-tslint-plugin`](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
[`code --install-extension dskwrk.vscode-generate-getter-setter`](https://marketplace.visualstudio.com/items?itemName=dskwrk.vscode-generate-getter-setter)


## #NodeJS

[`code --install-extension christian-kohler.npm-intellisense`](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
[`code --install-extension christian-kohler.path-intellisense`](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)


## #Vue

[`code --install-extension hollowtree.vue-snippets`](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)
[`code --install-extension octref.vetur`](https://marketplace.visualstudio.com/items?itemName=octref.vetur)


## #React

[`code --install-extension jawandarajbir.react-vscode-extension-pack`](https://marketplace.visualstudio.com/items?itemName=jawandarajbir.react-vscode-extension-pack)
[`code --install-extension msjsdiag.vscode-react-native`](https://marketplace.visualstudio.com/items?itemName=msjsdiag.vscode-react-native)


## #Angular

[`code --install-extension Angular.ng-template`](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
[`code --install-extension Mikael.Angular-BeastCode`](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)


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
