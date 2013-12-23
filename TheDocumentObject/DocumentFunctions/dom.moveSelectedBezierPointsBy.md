# dom.moveSelectedBezierPointsBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c92.html)

## バージョン

3

## 書式

dom.moveSelectedBezierPointsBy(delta)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the selected Bézier points are moved (see Point data type). For example, passing ({x:1,y:2}) moves the Bézier points 1 pixel to the right and 2 pixels down.

ベジェポイントを移動させるX/Y座標を指定するPoint型（Point型を参照）。例として、```{x:1,y:2}```を渡した場合、ベジェポイントは右へ1ピクセル・下へ2ピクセル移動します。

## 戻り値

なし

## 説明

If the selection contains at least one path with at least one Bézier point selected, this function moves all selected Bézier points on all selected paths by the specified amount.

選択範囲に少なくとも1つのパス上のベジェポイントが選択されている場合、この関数はパス上で選択したすべてのベジェポイントを指定量移動させます。