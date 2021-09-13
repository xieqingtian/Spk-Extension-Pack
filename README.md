# React VSCode Extension Pack

A collection of extensions for working with React Applications in VS Code

These are some of my favorite extensions to make React application development easier and fun.

## Extensions Included

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode&WT.mc_id=marketplace-pack-sdras)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [CSS Modules](https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules)
- [stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
- [ts-react-snippets](https://marketplace.visualstudio.com/items?itemName=xieqingtian.ts-react-snippets)

## My VScode Settings

```json
{
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
  "editor.formatOnSave": true,
  "editor.fontFamily": "JetBrains Mono, Consolas, 'Courier New', monospace",
  "editor.fontSize": 16,
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.stylelint": true
  },
  "todo-tree.general.tags": ["TODO", "FIXME", "XXX", "NOTE", "BUG", "HACK"],
  "todo-tree.highlights.defaultHighlight": {
    "foreground": "black",
    "type": "text"
  },
  "todo-tree.highlights.customHighlight": {
    "FIXME": {
      "icon": "flame",
      "iconColour": "orange",
      "background": "orange"
    },
    "TODO": {
      "icon": "check",
      "iconColour": "yellow",
      "background": "yellow"
    },
    "BUG": {
      "icon": "bug",
      "iconColour": "red",
      "background": "red"
    },
    "NOTE": {
      "icon": "note",
      "iconColour": "blue",
      "background": "blue"
    },
    "XXX": {
      "icon": "question",
      "iconColour": "green",
      "background": "green"
    },
    "HACK": {
      "icon": "alert",
      "iconColour": "purple",
      "background": "purple"
    }
  },
  "security.workspace.trust.untrustedFiles": "open",
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "source": "Git Bash",
      "path": ["C:\\Program Files\\Git\\bin\\bash.exe"],
      "icon": "terminal-bash"
    }
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "workbench.colorCustomizations": {
    "[Default Dark+]": {
      "editor.background": "#000000",
      "sideBar.background": "#000000"
    }
  }
}
```
