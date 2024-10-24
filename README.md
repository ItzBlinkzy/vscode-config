# My VSCode Configurations

This repository contains two distinct VSCode configurations: a minimalist setup optimized for keybindings and a standard setup with minor tweaks for a more UI-focused experience.

## 1. Minimalist Configuration
![Minimalist Config Screenshot](https://github.com/user-attachments/assets/bc39a9f3-2dd3-4098-b928-4700278b8cdf)
![Command Palette](https://github.com/user-attachments/assets/b59b5de7-23fa-4936-a3e7-f61a7996eb34)
![Tool Tips](https://github.com/user-attachments/assets/a507c5ec-f644-482d-b0e2-568bc5a240f8)

This setup is designed to declutter the workspace by removing unnecessary UI elements. It’s focused on maximising the view of code and relies heavily on keybindings to navigate and manage files.

### Key Features:
- **Activity Bar & Menu Bar Hidden**: Access these features through default keybindings to keep the interface clean.
- **Minimap Disabled**: Removed to provide more room for code.
- **Line Height Increased**: Slightly raised for better readability.
- **Filename Only in the Header**: Strips away extra information, showing only the file name at the top.
- **Explorer on the Right**: Moved to the right side to maximize horizontal space for code.
- **Centered Command Palette and Enhanced Tooltips**: Command palette is centered now with a background blur when accessed, new rounded clean modern design with slight gradient background of tooltips and colour palette.



### Required Extensions:
- [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

### Required Fonts:
- JetBrains Mono
- Geist Mono
- Monaspace Radon


### Instructions

1. Install "Custom CSS and JS Loader" VS Code Extension.
2. Copy the contents of this settings.json to your VS Code's settings.json (warning: it will overwrite your settings) make sure keep a backup to restore at any point.
3. Add `vscode_custom_css.imports` array to the settings.json file:
4. Link to the path of the css and js scripts below
```
"vscode_custom_css.imports": [
    // Absolute file paths for your css/js files
    // For Mac or Linux
    // "file:///Users/your-user-name/custom-vscode.css",
    // "file:///Users/your-user-name/custom-vscode-script.js"

    // For Windows
    // "file:///C:/path-of-custom-css/custom-vscode.css",
    // "file:///C:/path-of-custom-css/custom-vscode-script.js"
]
```

---

## 2. Standard Configuration

This is a near-default VSCode setup with a few keybinding changes and useful extensions. It’s more UI-focused and caters to those who prefer a traditional experience with minor customizations.

Only includes a settings.json file

### Extension List:
*Coming soon.*

**Main Themes used with both setups**:
* One Monokai
* Catppuccin Frappé


---
Feel free to clone and customize these configurations to suit your own workflow.
