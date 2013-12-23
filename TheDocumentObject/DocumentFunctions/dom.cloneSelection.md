# dom.cloneSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7eb2.html)

## バージョン

3

## 書式

```
dom.cloneSelection()
```

## 引数

なし

## 戻り値

なし

## 説明

Makes exact duplicates of the selection, placing the duplicated items directly on top of the original items.

選択範囲をオブジェクトの上に、同じオブジェクトを複製します。

## サンプル

The following command copies the selected items on top of the original items:

次のコマンドは、元のオブジェクトの上に選択したオブジェクトをコピーします。

```
fw.getDocumentDOM().cloneSelection();
```

## 参照

dom.duplicateSelection()