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

extensions (z cmd.exe code --list-extensions --show-versions > extensions.txt): 

Instalacja pluginow 
unix: code --install-extension $(cat extensions.txt)
windwos: code --list-extensions --show-versions | Out-File extensions.txt
```
bmewburn.vscode-intelephense-client@1.16.5
ericgomez.phpstorm-theme@1.0.21
github.copilot-chat@0.44.2
grogdunn.netbeans-keybindings@0.0.9
laravel.vscode-laravel@1.7.0
leodevbro.blockman@1.7.8
onecentlin.laravel-blade@1.38.0
```
