# dom.setDocumentCanvasColor()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7aa5.html)

## バージョン

3

## 書式

dom.setDocumentCanvasColor(color)

## 引数

### color:

A color string (see Color string data type).

Color String型。

## 戻り値

なし

## 説明

Sets the canvas color of the document to the specified color.

ドキュメントのカンバスカラーを指定した色に設定します。

## サンプル

The following command sets the canvas color to blue:

次のコマンドを実行すると、カンバスカラーを青に設定します。

```
fw.getDocumentDOM().setDocumentCanvasColor("#0000ff");
```