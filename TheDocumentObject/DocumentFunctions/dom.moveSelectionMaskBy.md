# dom.moveSelectionMaskBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c85.html)

## バージョン

4

## 書式

dom.moveSelectionMaskBy(delta)

## 引数

### delta:

A point that specifies the x-,y-coordinate values by which the mask is moved (see Point data type). For example, passing ({x:1,y:2}) moves the mask 1 pixel to the right and 2 pixels down.

マスクをの移動させるX/Y座標を指定するPoint型（Point型を参照）。例として、```{x:1,y:2}```を渡した場合、マスクは右へ1ピクセル・下へ2ピクセル移動します。

## 戻り値

なし

## 説明

Moves the current pixel mask by the specified amount. If there is no pixel selection, an exception is thrown.

現在のビットマップマスクを指定量移動させます。ピクセルの選択範囲がない場合、例外をスローします。