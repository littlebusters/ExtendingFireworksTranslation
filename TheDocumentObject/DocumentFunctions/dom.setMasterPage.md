# dom.setMatteColor()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-799c.html)

## バージョン

3

## 書式

dom.setMatteColor(bUseMatteColor, matteColor)

## 引数

### bUseMatteColor:

Boolean. If true, the document’s matte color is set to the value that is specified by matteColor. If false, any matte color is removed from the document, and the second argument is ignored. 

Boolean型。```true```ならば、ドキュメントのマットカラーをmatteColorで指定された値に設定します。```false```の場合、ドキュメントのマットカラーをドキュメントから削除し、第2引数は無視されます。

### matteColor:

A color string (see Color string data type).

ColorString型（ColorString型を参照）

## 戻り値

なし

## 説明

Sets or removes the document’s matte color that is used for exporting. 

書き出しで使用する、ドキュメントのマットカラーの設定または削除をします。

## サンプル

The following command sets the matte color to blue:

次のコマンド実行すると、マットカラーをブルーに設定します。

```
fw.getDocumentDOM().setMatteColor(true, "#0033ff");
```