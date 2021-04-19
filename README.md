# FontPicker_ahk2
Font Picker for AHK v2

## FontSelect()
```
fontObj := FontSelect(fontObject:="", hwnd:=0, Effects := true)
```

The input `fontObject` is for initializing the dialog with specific values.

The `hwnd` will make the specified window handle the parent.

Setting `Effects` to false will disable the changing of strike, underline, and other styles.

The return `fontObj` is generally meant for future use to re-open the dialog with the settings last used.