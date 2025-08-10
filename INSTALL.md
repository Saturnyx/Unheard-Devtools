# Installation
## If scoop ain't installed
Open a PowerShell terminal (version 5.1 or later) and from the PS C:\> prompt, run:
``` powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Add the bucket
``` powershell
scoop bucket add unheard-devtools https://github.com/saturnyx/unheard-devtools
```

## Install apps
``` powershell
scoop install unheard-devtools/<tool-name>
```
