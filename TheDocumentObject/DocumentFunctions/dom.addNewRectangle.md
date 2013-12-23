# dom.addNewRectangle()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f88.html)

## バージョン

3

## 書式

```
dom.addNewRectangle(boundingRectangle, roundness)
```

## 引数

### boundingRectangle:

新しく追加される矩形の大きさを指定した、Rectangle型。

### roundness:

角丸の大きさを指定する、0から1までのFloat型。（0は角丸なし、1は100%の角丸です）

## 戻り値

なし

## 説明

指定した大きさの矩形または角丸のついた矩形を追加します。矩形は現在のパス属性を利用し、現在のフレームとレイヤーに追加されます。

## サンプル

次のコマンドは、指定した座標内に新しい角丸の矩形を追加します。

```
fw.getDocumentDOM().addNewRectangle({left:0, top:0, right:100, bottom:100}, 0);
```

## 次を参照

dom.addNewRectanglePrimitive()
