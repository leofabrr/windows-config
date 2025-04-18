# Config Windows

TASKKILL /F /IM msedge.exe  
RD /S /Q "C:\Program Files (x86)\Microsoft\Edge"  
RD /S /Q "C:\Program Files\Microsoft\Edge"  
RD /S /Q "C:\Users\%USERNAME%\AppData\Local\Microsoft\Edge"

Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}]

[HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32]
@=""

