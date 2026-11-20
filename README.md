# .vscode

My personal Visual Studio Code configuration, including the settings, themes, and extensions I use.

Feel free to explore, use, or adapt anything to your own workflow.

This repository is licensed under the [MIT License](./LICENSE).

---

## settings.json

```json
{
    // UI
    "material-icon-theme.languages.associations": {},
    "material-icon-theme.files.associations": {},
    "workbench.iconTheme": "material-icon-theme",
    "workbench.activityBar.location": "top",
    "workbench.sideBar.location": "right",
    "window.menuBarVisibility": "compact",
    "workbench.editor.showTabs": "multiple",
    "window.commandCenter": false,
    "chat.titleBar.signIn.enabled": false,
    "workbench.layoutControl.enabled": false,
    "chat.titleBar.openInAgentsWindow.enabled": false,
    "workbench.browser.showInTitleBar": false,

    // Typography
    "editor.fontFamily": "'JetBrains Mono'",
    "editor.fontSize": 14,
    "editor.fontWeight": "500",
    "editor.fontLigatures": true,
    "editor.lineHeight": 1.6,
    "terminal.integrated.fontFamily": "JetBrains Mono",
    "terminal.integrated.fontWeight": "500",

    // Formating
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 4,

    // Minimap
    "editor.minimap.autohide": "mouseover",

    // Files
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 100,

    // Themes
    "workbench.colorTheme": "One Dark Pro Darker"
}
```

---

## extensions.json

```json
{
    "recommendations": [
        // Git
        "donjayamanne.githistory", // Git History
        "eamodio.gitlens", // Git Lens
        "mhutchie.git-graph", // Git Graph
        "GitHub.remotehub", // GitHub Repositories

        // Themes
        "GitHub.github-vscode-theme", // GitHub Theme
        "zhuangtongfa.material-theme", // One Dark Pro Theme

        // Other
        "PKief.material-icon-theme", // Material Icon Theme
        "usernamehw.errorlens", // Error Lens
        "esbenp.prettier-vscode", // Prettier
        "formulahendry.auto-rename-tag", // Auto Rename Tag
        "aaron-bond.better-comments", // Better Comments
        "streetsidesoftware.code-spell-checker", // Code Spell Checker
        "ritwickdey.LiveServer", // Live Server
        "christian-kohler.path-intellisense", // Path Intellisense
        "quicktype.quicktype" // Paste JSON as Code
    ]
}
```

---

## .prettierrc

```json
{
    "tabWidth": 4,
    "useTabs": false
}
```

---
