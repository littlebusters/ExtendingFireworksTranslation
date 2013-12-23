# dom.clipCopyAsPaths()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ee8.html)

## バージョン

MX

## 書式

```
dom.clipCopyAsPaths()
```

## 引数

なし

## 戻り値

なし

## 説明

Copies the selection to the clipboard in Adobe Illustrator format.

選択範囲を Adobe Illustrator 形式でクリップボードへコピーします。

## サンプル

The following command copies the selected items to the clipboard in Adobe Illustrator format:

次のコマンドは、選択しているオブジェクトを Adobe Illustrator 形式でクリップボードへコピーします。

```
fw.getDocumentDOM().clipCopyAsPaths();
```