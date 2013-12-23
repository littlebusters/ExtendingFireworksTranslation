# dom.clipCut()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7edb.html)

## バージョン

3

## 書式

```
dom.clipCut()
```

## 引数

なし

## 戻り値

なし

## 説明

Cuts the selection to the clipboard.

選択範囲をクリップボードへ切り取ります。

## 例

The following command cuts the selected items and places them on the clipboard:

次のコマンドを実行すると、選択されたオブジェクトを切り取り、クリップボードに収めます。

```
fw.getDocumentDOM().clipCut();
```