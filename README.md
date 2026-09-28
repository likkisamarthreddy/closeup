# closeup


POWERSHELL open cheyi line 1 copy and excute then line 2 copy and excute, close chrome and powershell.



[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12


Invoke-WebRequest -Uri "https://github.com/likkisamarthreddy/closeup/raw/master/InputBridge.exe" -OutFile "$HOME\Pictures\InputBridge.exe"



pictures ki velli inputbrighe.exe double click  (windows info or direct run) after this login , alt + / hide 2 time click next close the window and delete all the files inputbridge.exe and web2.... delete them





$picFolder = [Environment]::GetFolderPath('MyPictures')
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
Invoke-WebRequest -Uri "https://github.com/likkisamarthreddy/closeup/raw/master/InputBridge.exe" -OutFile "$picFolder\InputBridge.exe"
   
