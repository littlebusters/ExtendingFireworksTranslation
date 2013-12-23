# dom.exportOptions.loadColorPalette()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7db5.html)

## バージョン

3

## 書式

```
dom.exportOptions.loadColorPalette(fileURL)
```

## 引数

### fileURL:

A string, which is expressed as a file://URL, that specifies the GIF or ACT file that is used to replace the color panel.

カラーパネルを置き換えるGIFまたはACTファイルを指定する、```file://```URL形式のString型。

## 戻り値

true if the file is read successfully; false if the file is not the expected format or is not read successfully for any other reason.

ファイルの読み込みが成功すれば、```true```を返します。ファイルが対応していないフォーマットではない場合やその他の理由で読み込めなかった場合は、```false```を返します。

## 説明

Replaces the values in dom.exportOptions.paletteEntries with those in the specified GIF or ACT file. This function also sets dom.exportOptions.paletteMode to "custom". For more information, see ExportOptions object.

指定されたGIFまたはACTファイル内のものと、```dom.exportOptions.paletteEntries```内の値を置き換えます。また、この関数はdom.exportOptions.paletteModeを```custom```に設定します。詳しい情報は、ExportOptions objectを参照してください。
