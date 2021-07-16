# win-regedit-directory

**regedit.exe**

"C:\Windows\regedit.exe"

コンピューター\HKEY_CLASSES_ROOT\Directory\shell\VSCode

コンピューター\HKEY_CLASSES_ROOT\Directory\shell\VSCode\command

"C:\Users\lightbox\AppData\Local\Programs\Microsoft VS Code\Code.exe" "%V"
```reg
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\shell\VSCode]
@=hex(2):43,00,6f,00,64,00,65,00,20,00,67,30,8b,95,4f,30,00,00
"Icon"=hex(2):43,00,3a,00,5c,00,55,00,73,00,65,00,72,00,73,00,5c,00,6c,00,69,\
  00,67,00,68,00,74,00,62,00,6f,00,78,00,5c,00,41,00,70,00,70,00,44,00,61,00,\
  74,00,61,00,5c,00,4c,00,6f,00,63,00,61,00,6c,00,5c,00,50,00,72,00,6f,00,67,\
  00,72,00,61,00,6d,00,73,00,5c,00,4d,00,69,00,63,00,72,00,6f,00,73,00,6f,00,\
  66,00,74,00,20,00,56,00,53,00,20,00,43,00,6f,00,64,00,65,00,5c,00,43,00,6f,\
  00,64,00,65,00,2e,00,65,00,78,00,65,00,00,00

[HKEY_CLASSES_ROOT\Directory\shell\VSCode\command]
@=hex(2):22,00,43,00,3a,00,5c,00,55,00,73,00,65,00,72,00,73,00,5c,00,6c,00,69,\
  00,67,00,68,00,74,00,62,00,6f,00,78,00,5c,00,41,00,70,00,70,00,44,00,61,00,\
  74,00,61,00,5c,00,4c,00,6f,00,63,00,61,00,6c,00,5c,00,50,00,72,00,6f,00,67,\
  00,72,00,61,00,6d,00,73,00,5c,00,4d,00,69,00,63,00,72,00,6f,00,73,00,6f,00,\
  66,00,74,00,20,00,56,00,53,00,20,00,43,00,6f,00,64,00,65,00,5c,00,43,00,6f,\
  00,64,00,65,00,2e,00,65,00,78,00,65,00,22,00,20,00,22,00,25,00,56,00,22,00,\
  00,00
```

```reg
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\shell\usercmd]
@="コマンドプロンプトをここで開きたい(&P)"

[HKEY_CLASSES_ROOT\Directory\shell\usercmd\command]
@="cmd.exe /s /k pushd \"%V\""
```
