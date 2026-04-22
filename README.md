# Konfig pod vscode
```
{
    "chat.disableAIFeatures": true,
    "editor.fontLigatures": false,
    "chat.agent.enabled": false,
    "chat.agent.maxRequests": 0,
    "workbench.colorTheme": "PhpStorm Dark",
    "editor.minimap.enabled": false,
    "explorer.autoReveal": false,
    "editor.inlayHints.enabled": "off",
    "workbench.colorCustomizations": {
        "editor.lineHighlightBackground": "#1073cf2d",
        "editor.lineHighlightBorder": "#9fced11f"
    },
    "editor.wordWrap": "off",
    "diffEditor.wordWrap": "off",
    "editor.guides.indentation": false,
    "editor.guides.bracketPairs": false,
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash",
            "icon": "terminal-git-bash"
        },
        "Ubuntu (WSL)": {
            "path": "C:\\WINDOWS\\System32\\wsl.exe",
            "args": [
                "-d",
                "Ubuntu"
            ]
        }
    },
    "terminal.integrated.defaultProfile.windows": "Ubuntu (WSL)",
    "extensions.ignoreRecommendations": true
}
```

keybindings.json
```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "shift shift",
        "command": "workbench.action.quickOpen"
    }
]
```
