# dom.clipPasteAttributes()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ec7.html)

## バージョン

3

## 書式

```
dom.clipPasteAttributes()
```

## 引数

なし

## 戻り値

なし

## 説明

Pastes the attributes from the clipboard onto the selection.
 
クリップボード上の属性を選択範囲に貼り付けます。

## サンプル

The following command applies the attributes that were copied to the clipboard onto the selected items:

次のコマンドを実行すると、クリップボードにコピーされた属性を選択したオブジェクトに適用します。

```
fw.getDocumentDOM().clipPasteAttributes();
```