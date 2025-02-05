# ahk-portable-windows-powershell
```powershell
$WebClient=New-Object Net.WebClient
$Uri='https://www.autohotkey.com/download/ahk-v2.zip'
$WebClient.DownloadFile($Uri, "$Home/downloads/ahk-v2.zip")
```
