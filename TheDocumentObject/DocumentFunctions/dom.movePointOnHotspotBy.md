# dom.movePointOnHotspotBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c9e.html)

## バージョン

3

## 書式

dom.movePointOnHotspotBy(ptToModifyIndex, delta)

## 引数

### ptToModifyIndex:

A zero-based index that specifies which point on the path is to move.

移動するパス上のポイントを指定する、0から始まるインデックス。

### delta:

A point that specifies the x,y coordinate values by which the point is moved (see Point data type). For example, passing ({x:1,y:2}) moves the point 1 pixel to the right and 2 pixels down.

ポイントを移動させるX/Y座標を指定するPoint型（Point型を参照）。例として、```{x:1,y:2}```を渡した場合、ポイントは右へ1ピクセル・下へ2ピクセル移動します。

## 戻り値

なし

## 説明

If the selection is a hotspot or slice of the polyline variety, this function moves a point on the hotspot’s path by the specified amount.

選択範囲がホットスポットまたは多角形スライスの場合、この関数はパス上のポイントを指定量移動させます。