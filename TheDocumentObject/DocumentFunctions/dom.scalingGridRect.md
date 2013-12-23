# dom.scalingGridRect()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b80.html)

## バージョン

9

## 書式

dom.scalingGridRect(left, top, right, bottom)

## 引数

### bounds

Specifies the bounds of the grid rectangle. 

グリッド矩形の境界を指定します。

## 戻り値

なし

## 説明

Sets the positions of the 9-slice scaling guides by specifying the size of the rectangle they surround.

矩形を囲むサイズを指定することで、9スライスガイドの位置を設定します。

## サンプル

The following command sets the 9-slice scaling grid rectangle to -50, -50, 50, 50:

次のコマンド実行すると、9スライスガイドの矩形を、-50, -50, 50, 50に設定します。

```
fw.getDocumentDOM().scalingGridRect({-50, -50, 50, 50});
```
