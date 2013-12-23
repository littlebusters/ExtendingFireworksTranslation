# dom.exportOptions.saveColorPalette()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7daf.html)

## バージョン

3

## 書式

```
dom.exportOptions.saveColorPalette(fileURL)
```

## 引数

### fileURL:

A string, which is expressed as a file://URL, that specifies the name of the file to which the color panel should be saved. Do not specify a file extension; the .act extension is added automatically. 

カラーパネルを保存するファイル名を```file://```URL形式で指定したString型。ファイル拡張子は指定市内でください。.act拡張子が自動的に追加されます。

## 戻り値

なし

## 説明

Saves the values in dom.exportOptions.paletteEntries to the specified color panel (ACT file). This function does not modify the document. For more information, see ExportOptions object.

指定されたカラーパネル（actファイル）に、```dom.exportOptions.paletteEntries```の値を保存します。この関数は、ドキュメントを変更しません。詳しい情報は、ExportOptions objectを参照してください。