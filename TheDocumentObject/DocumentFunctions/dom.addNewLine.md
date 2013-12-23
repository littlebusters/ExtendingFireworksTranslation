# dom.addNewLine()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f96.html)

## バージョン

3

## 書式

```
dom.addNewLine(startPoint, endPoint)
```

## 引数

### startPoint / endPoint

Points型。それぞれで指定されたX・Y座標を基にパスを追加します。（Point型を参照）

## 戻り値

新しいレイヤー名を含むString値。

## 説明

2点間に新しいパスを追加します。新しいパスは、ドキュメントで設定されているパス属性で、現在のレイヤーとフレームに追加されます。

## サンプル

次のコマンドは、指定された座標間で、新しい線を追加します。

```
fw.getDocumentDOM().addNewLine({x:64.5, y:279.5}, {x:393.5, y:421.5});
```
