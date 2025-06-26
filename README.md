# code-settings

## vscode `settings.json`

```json
{
  "terminal.integrated.inheritEnv": false,
  "python.defaultInterpreterPath": "/Users/afyqeyzar/opt/anaconda3/bin/python",
  "cSpell.userWords": [
    "afyq",
    "colours",
    "Datajson",
    "descr",
    "eyzar",
    "favourite",
    "knexfile",
    "matplotlib",
    "minimiser",
    "nodrag",
    "pannable",
    "Pinterest",
    "pyplot",
    "reactflow",
    "Zaharoff",
    "zoomable"
  ],
  "workbench.colorTheme": "Dark+ (color blind)",
  "editor.tabSize": 2,
  "explorer.confirmDelete": false,
  "[python]": {
    "editor.formatOnType": true,
    "editor.defaultFormatter": "ms-python.black-formatter"
  },
  "explorer.confirmDragAndDrop": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.iconTheme": "material-icon-theme",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "prettier.bracketSameLine": true,
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.inlayHints.enabled": "off",
  "workbench.colorCustomizations": {
    "editor.lineHighlightBackground": "#1073cf2d",
    "editor.lineHighlightBorder": "#9fced11f",
    "statusBar.background": "#1A1A1A",
    "statusBar.noFolderBackground": "#212121",
    "statusBar.debuggingBackground": "#263238"
  },
  "editor.wordWrap": "off",
  "diffEditor.wordWrap": "off",
  "editor.guides.indentation": false,
  "editor.guides.bracketPairs": false,
  "terminal.integrated.env.osx": {},
  "console-ninja.featureSet": "Community",
  "console-ninja.toolsToEnableSupportAutomaticallyFor": {
    "live-server-extension": true
  },
  "window.zoomLevel": 0.2,
  "explorer.confirmPasteNative": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.stickyScroll.enabled": true,
  "editor.minimap.enabled": false,
  "workbench.activityBar.location": "hidden",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.snippetSuggestions": "top",
  "editor.tabCompletion": "onlySnippets",
  "editor.linkedEditing": true,
  "workbench.sideBar.location": "right",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "workbench.statusBar.visible": false,
  "files.associations": {
    "*.css": "tailwindcss"
  },
  "[snippets]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "explorer.fileNesting.patterns": {
    "*.ts": "${capture}.js",
    "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
    "*.jsx": "${capture}.js",
    "*.tsx": "${capture}.ts",
    "tsconfig.json": "tsconfig.*.json",
    "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
    "*.sqlite": "${capture}.${extname}-*",
    "*.db": "${capture}.${extname}-*",
    "*.sqlite3": "${capture}.${extname}-*",
    "*.db3": "${capture}.${extname}-*",
    "*.sdb": "${capture}.${extname}-*",
    "*.s3db": "${capture}.${extname}-*"
  },

  "editor.lineHeight": 0,
  "editor.fontSize": 10,
  "workbench.editorAssociations": {
    "git-rebase-todo": "default"
  }
  // "workbench.editor.showTabs": "none"
}
```

## terminal alias
```bash
alias gap="git add -p"
alias gs="git status"
alias nd="npm run dev"
alias v="nvim ."
alias vim="nvim"
alias cl="clear"
alias lg="lazygit"
```
