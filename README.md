# gpl-palette-generator


Source file must contains colors in hex, for example in.txt:
```
#1abc9c
#16a085
#f1c40f
#f39c12
#2ecc71
#27ae60
#e67e22
#d35400
#3498db
#2980b9
#e74c3c
#c0392b
#9b59b6
#8e44ad
#ecf0f1
#bdc3c7
#34495e
#2c3e50
#95a5a6
#7f8c8d
```


Usage:
1) Generate palette:

```
gplpalette.CreatePaletteFromFile(inputFileName string, paletteName string, columnsCount int)
```

where: 

`inputFileName` - path to source file with colors as hex string

`paletteName` - name of palette

`columnsCount` - columns count for palette in graphics editor (GIMP, inkscape)


2) Place generated *.gpl file to /usr/share/[APP]/palettes/
where `[APP]` gimp or inkscape
