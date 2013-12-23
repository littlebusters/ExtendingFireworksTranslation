# dom.setOpacity()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7987.html)

## バージョン

3

## 書式

dom.setOpacity(opacity)

## 引数

### opacity

A float variable between 0 and 100, inclusive.

0から100までのFloat型。

## 戻り値

なし

## 説明

Sets the opacity of the selection to the specified value.

選択範囲の不透明度を指定した値に設定します。

## サンプル

The following command sets the selected item to an opacity of 55%:

次のコマンドを実行すると、選択しているオブジェクトの不透明度を55%に設定します。

```
fw.getDocumentDOM().setOpacity(55);
```
