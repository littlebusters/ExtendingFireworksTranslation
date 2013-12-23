# dom.moveMaskGroupContentsBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cab.html)

## バージョン

3

## 書式

dom.moveMaskGroupContentsBy(delta)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the element is moved (see Point data type). For example, passing ({x:1,y:2}) moves the element 1 pixel to the right and 2 pixels down.

移動させるオブジェクトのX/Y座標を指定するPoint型（Point型を参照）。例えば、```{ x: 1, y: 2 }```を渡すと、要素を右に1ピクセル・下に2ピクセル移動させます。

## 戻り値

なし

## 説明

If the selection is a mask group, this function moves the contents within the mask group by the specified amount. If the selected element has an element mask, this function moves the element (not the element mask) by the specified amount.

選択範囲がマスクグループだった場合、この関数はマスクグループに含まれるコンテンツ（オブジェクト）を指定された量だけ移動させます。選択された要素が要素マスクを持っている場合、この関数は要素（要素マスクではない）を指定された量だけ移動させます。

## 参照

dom.moveElementMaskBy()