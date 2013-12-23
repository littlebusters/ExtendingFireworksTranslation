# dom.moveElementMaskBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fbe.html)

## バージョン

4

## 書式

dom.moveElementMaskBy(delta)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the element masks are moved (see Point data type). For example, passing ({x:1,y:2}) moves the element masks 1 pixel to the right and 2 pixels down.

要素マスクを移動させるX/Y座標を指定するPoint型（Point型を参照）。例えば、```{ x: 1, y: 2 }```を渡すと、要素マスクが右に1ピクセル・下に2ピクセル移動します。

## 戻り値

なし

## 説明

For all the elements in the selection that have element masks (linked or unlinked), it moves the element masks by the specified amount. Elements without element masks are ignored. If no elements in the selection have element masks, an exception is thrown.

選択範囲に含まれる要素マスク（リンク/リンク解除）を、指定された量で移動させます。要素マスクがないオブジェクトは無視されます。選択範囲に要素マスクを持つオブジェクトがない場合は、例外がスローされます。
