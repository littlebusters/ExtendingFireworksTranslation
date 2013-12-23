# dom.exportTo()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7da9.html)

## バージョン

3

## 書式

```
dom.exportTo(fileURL, {exportOptions})
```

## 引数

### fileURL:

A string, which is expressed as a file://URL, that specifies the name of the exported file.

```file://```URL形式でファイル名を指定するString型。

### exportOptions:

An ExportOptions object (see ExportOptions object). This argument is optional. If this argument is omitted or null, the document’s current Export Options settings are used. If values are passed in with exportOptions, they are used for this export operation only; they do not change the document’s exportOptions property.

ExportOptions object（ExportOptions objectを参照）。この引数はオプションです。この引数を省略または```null```の場合、ドキュメントに設定されている書き出しオプションを使用します。exportOptionsが渡された場合、この書き出し操作のみに使用され、ドキュメントの書き出し設定は変更しません。

## 戻り値

true if the file is successfully exported; false otherwise.

書き出しが成功すれば```true```、それ以外は```false```です。

## 説明

Exports the document as specified.

指定されたドキュメントに書き出しします。