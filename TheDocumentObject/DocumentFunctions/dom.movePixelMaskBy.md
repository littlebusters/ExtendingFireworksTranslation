# dom.movePixelMaskBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ca4.html)

## バージョン

4

## 書式

dom.movePixelMaskBy(delta)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the bitmap mode selection is moved (see Point data type). For example, passing ({x:1,y:2})moves the bitmap mode selection 1 pixel to the right and 2 pixels down.

ビットマップモードの選択範囲を移動させるX/Y座標を指定するPoint型（Point型を参照）。例として、```{x:1,y:2}```を渡した場合、ビットマップモードの選択範囲は、右へ1ピクセル・下へ2ピクセル移動します。

## 戻り値

なし

## 説明

Moves a bitmap mode selection by the specified amount, without moving the pixels that are within the selection.

選択範囲内のピクセルを移動させず、ビットマップモードの選択範囲を指定量移動します。