# Windaube-Reminders
Useful stuff for M$ Windaube installations

## get architecture
( exec > cmd > ) ```wmic OS get architecture```

## God Mode
( create dir & rename ) ```GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}````

## disable / enable UAC ( User Access Control, the annoying "need your authorization to do stg" popup )
Disable UAC:  
```C:\Windows\System32\cmd.exe /k %windir%\System32\reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 0 /f```

Enable UAC:  
```C:\Windows\System32\cmd.exe /k %windir%\System32\reg.exe ADD HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System /v EnableLUA /t REG_DWORD /d 1 /f```
