VS Code Theme Settings
This repository contains the settings.json configuration file for Visual Studio Code, optimized for a personalized theme experience. These settings ensure consistent and visually appealing theme usage while enhancing code readability and productivity.

🎨 Features
Custom Theme: Automatically applies your preferred VS Code theme.
Font Customization: Configures font family, size, and ligatures for better code aesthetics.
Editor Tweaks: Includes custom settings for editor line height, cursor style, and bracket pairing.
Color Customizations: Allows for overrides of specific UI and syntax colors.
⚙️ Settings Overview
Below is a summary of the settings.json configurations:

1. Theme Configuration
Specifies the VS Code theme.

json
Copy code
"workbench.colorTheme": "Your Preferred Theme Name",
"workbench.iconTheme": "material-icon-theme"
2. Font Settings
Customizes the editor font for clarity and style.

json
Copy code
"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
"editor.fontSize": 14,
"editor.fontLigatures": true
3. Color Customizations
Allows specific overrides for colors in the theme.

json
Copy code
"workbench.colorCustomizations": {
    "editorLineNumber.foreground": "#FF6347",
    "editorBracketMatch.border": "#00FF00",
    "tab.activeBackground": "#1E1E1E",
    "activityBarBadge.background": "#007ACC"
}
4. Editor Settings
Configures the overall look and feel of the editor.

json
Copy code
"editor.cursorStyle": "line",
"editor.lineHeight": 22,
"editor.minimap.enabled": false,
"editor.formatOnSave": true
5. Bracket Pairing and Guides
Improves readability with bracket matching and guides.

json
Copy code
"editor.guides.bracketPairs": true,
"editor.bracketPairColorization.enabled": true
📋 Full settings.json
json
Copy code
{
    "workbench.colorTheme": "Your Preferred Theme Name",
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
    "editor.fontSize": 14,
    "editor.fontLigatures": true,
    "workbench.colorCustomizations": {
        "editorLineNumber.foreground": "#FF6347",
        "editorBracketMatch.border": "#00FF00",
        "tab.activeBackground": "#1E1E1E",
        "activityBarBadge.background": "#007ACC"
    },
    "editor.cursorStyle": "line",
    "editor.lineHeight": 22,
    "editor.minimap.enabled": false,
    "editor.formatOnSave": true,
    "editor.guides.bracketPairs": true,
    "editor.bracketPairColorization.enabled": true
}
🛠️ How to Use
Open Visual Studio Code.
Go to File > Preferences > Settings (or press Ctrl+,).
Search for settings.json and click Edit in settings.json.
Replace the content with the provided JSON or merge it with your existing settings.
Save the file and restart VS Code to apply the changes.
🌟 Recommended Extensions
To enhance the theme further, consider installing the following extensions:

Material Icon Theme
Fira Code Font
Bracket Pair Colorizer
Feel free to customize the settings to suit your preferences! If you have suggestions for improvement, please create an issue or a pull request.

Happy coding! 🚀

