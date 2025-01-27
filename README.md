# VS Code Settings Configuration

This repository contains a customized `settings.json` file for Visual Studio Code, tailored to enhance the development experience with specific themes, extensions, and configurations.

---

## 🎨 Features

- **Custom Themes and Backgrounds**: Includes `Alma Dimmed Sakura` theme, custom backgrounds, and stickers.
- **Optimized Editor Settings**: Tab size, formatter, and language-specific settings.
- **Enhanced UI Customizations**: Adjustments to color themes, transparency, and sidebar visibility.
- **Extension Integrations**: Pre-configured settings for popular extensions like Emmet, Material Icon Theme, and Console Ninja.
- **Minimized Distractions**: Hides activity bar and status bar for a cleaner interface.

---

## ⚙️ Key Settings

### 1. **Workspace Trust**
Automatically opens untrusted files without prompting.
```json
{
  "security.workspace.trust.untrustedFiles": "open",
  "explorer.openEditors.visible": 0,
  "glassit.alpha": 250,
  "vscode-pets.theme": "castle",
  "vscode-pets.throwBallWithMouse": true,
  "doki.statusbar.name": "aoko",
  "doki.sticker.path": "D:\\Pictures\\kohaku-melty-blood.gif",
  "doki.sticker.css": "background-position: 100% 100%; background-size: 10%;",
  "doki.background.enabled": false,
  "doki.wallpaper.enabled": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.tabSize": 2,
  "terminal.integrated.env.windows": {},
  "console-ninja.featureSet": "Community",
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "auto-rename-tag.activationOnLanguage": [
    "*"
  ],
  "workbench.colorCustomizations": {
    "tab.activeBackground": "#230202",
    "tab.inactiveBackground": "#000000",
    "titleBar.activeBackground": "#230202",
    "sideBarSectionHeader.background": "#230202",
    "breadcrumb.background": "#000000",
    "activityBar.background": "#000000",
    "editorLineNumber.activeForeground": "#f32c2c",
    "editorLineNumber.foreground": "#e49f9f",
    "editorGutter.background": "#000000",
    "minimap.background": "#000000",
    "editor.lineHighlightBackground": "#230202",
    "editor.selectionBackground": "#6c2222",
    "editor.background": "#000000",
    "sideBar.background": "#000000",
    "panel.background": "#000000",
    "terminal.background": "#000000",
    "tab.hoverBackground": "#230202",
    "list.hoverBackground": "#230202",
    "list.activeSelectionBackground": "#400808",
    "list.inactiveSelectionBackground": "#230202",
    "editorSuggestWidget.background": "#230202"
  },
  "workbench.colorTheme": "Alma Dimmed Sakura",
  "background.editorBackgrounds": [
    "d:/Pictures/slideshow_bg/void_shiki_head.jpg"
  ],
  "background.backgroundAlignment": [
    "Center Center",
    "Top Center",
    "Top Center",
    "Top Center"
  ],
  "background.sidebarBackgrounds": [
    "d:/Pictures/saved_pictures/Ryougi.Shiki.full.1783279.jpg"
  ],
  "background.panelBackgrounds": [
    "d:/Pictures/saved_pictures/ryougi_shiki_wide.jpg"
  ],
  "php.validate.executablePath": "",
  "editor.minimap.size": "fill",
  "editor.minimap.showSlider": "always",
  "editor.minimap.enabled": false,
  "prisma.showPrismaDataPlatformNotification": false,
  "workbench.iconTheme": "material-icon-theme",
  "background.backgroundOpacity": [
    0.9,
    1,
    1,
    1
  ],
  "C_Cpp.default.compilerPath": "C:/MinGW/bin/g++.exe",
  "C_Cpp.default.includePath": [
    "${workspaceFolder}/**",
    "C:\\SFML-2.6.1\\include",
    "C:\\SFML-2.6.1\\bin"
  ],
  "background.backgroundBlur": [
    "0",
    "0",
    "0",
    "0"
  ],
  "workbench.activityBar.visible": false,
  "workbench.statusBar.visible": false
}

