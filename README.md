# vscode-settings
## Windows
```
cd %AppData%\Code\User
rename settings.json settings.json.bk
mklink settings.json %HOMEPATH%\git\vscode-settings\settings.json

rename keybindings.json keybindings.json.bk
mklink keybindings.json %HOMEPATH%\git\vscode-settings\keybindings.json
```