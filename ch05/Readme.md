在屏幕上显式文本

```
cmd /k pushd "$(CURRENT_DIRECTORY)" & D:\InstallPath\nasm\nasm.exe -f bin  "$(FULL_CURRENT_PATH)" -o "$(NAME_PART).bin" -l "$(NAME_PART).lst" & PAUSE & EXIT
```