# vscode-settings
## Windows
```
cd %homepath%\AppData\Roaming\Code\User
rename settings.json settings.json.bk
mklink settings.json %homepath%\git\vscode-settings\settings.json

rename keybindings.json keybindings.json.bk
mklink keybindings.json %homepath%\git\vscode-settings\keybindings.json
```