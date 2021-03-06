# React VSCode Extension Pack

A collection of extensions for working with React Applications in VS Code

These are some of my favorite extensions to make React application development easier and fun.

## Extensions Included

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&WT.mc_id=marketplace-pack-sdras)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
- [Chinese (Simplified) Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-zh-hans)
- [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
- [ts-react-snippets](https://marketplace.visualstudio.com/items?itemName=xieqingtian.ts-react-snippets)

## My VScode Settings

```json
{
  "workbench.colorTheme": "One Dark Pro",
  "editor.formatOnSave": true,
  "terminal.integrated.shell.windows": "F:\\Git\\bin\\bash.exe",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[less]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "tasklist",
      "foreground": "white",
      "background": "yellow",
      "iconColour": "yellow",
      "opacity": 0.6
    },
    "FIXME": {
      "icon": "bug",
      "foreground": "white",
      "iconColour": "#f5222d",
      "background": "#f5222d",
      "opacity": 0.6
    },
    "HACK": {
      "icon": "rocket",
      "foreground": "white",
      "iconColour": "#40a9ff",
      "background": "#40a9ff",
      "opacity": 0.6
    }
  },
  "todo-tree.filtering.excludedWorkspaces": ["node_modules/**/*"]
}
```
