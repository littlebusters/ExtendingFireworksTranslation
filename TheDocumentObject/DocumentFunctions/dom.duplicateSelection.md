# dom.duplicateSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7dff.html)

## バージョン

3

## 書式

```
dom.duplicateSelection()
```

## 引数

なし

## 戻り値

なし

## 説明

Makes a duplicate of the selection, offsetting it slightly from the original.

選択範囲を元から少しオフセットして複製します。

## サンプル

The following command duplicates the selected items:

次のコマンドを実行すると、選択したオブジェクトを複製します。

```
fw.getDocumentDOM().duplicateSelection();
```

## 参照

dom.cloneSelection()