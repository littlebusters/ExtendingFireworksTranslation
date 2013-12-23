# fw.exportDocumentAs()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WSFE7661B7-16E5-4d6f-8DD9-52182411185D.html)

## バージョン

3

## 書式

```
fw.exportDocumentAs(document, fileURL, exportOptions)
```

## 引数

### document:

ドキュメントオブジェクト。例えば```fw.documents[2]```は、書き出しするドキュメントを指定します。ドキュメントの指定がない（null）の場合は、アクティブなドキュメントが書き出しされます。

### fileURL:

書き出されたファイルのファイル名を指定した```file://URL```として表現されるString型。fileURLがnullの場合、「名前を付けて保存」ダイアログボックスが表示されます。

### exportOptions:

ExportOptionsオブジェクト（ExportOptionsオブジェクトを参照）。exportOptionsがNullの場合、ドキュメントの書き出しオプションが使用されます。exportOptionsで指定されたファイル形式と、fileURLで指定されたファイル形式が異なる場合、fileURLをexportOptionsで指定された形式に変更されます。

## 戻り値

Boolean型。成功した場合は```true```、失敗した場合は```false```。

## 説明

指定されたドキュメントを指定したファイルに書き出しします。

## 参照

fw.exportHtmlAndImages()
