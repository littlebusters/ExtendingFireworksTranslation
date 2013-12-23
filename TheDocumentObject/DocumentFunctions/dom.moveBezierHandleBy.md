# dom.moveBezierHandleBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cbd.html)

## バージョン

3

## 書式

dom.moveBezierHandleBy(whichPath, contourIndex, ptToModify, deltaControlPointFirst, deltaControlPointLast)

## 引数

### whichPath:

A zero-based index that specifies an index into the list of selected items, indicating which item contains the Bézier handles to move.

移動するハンドルが含まれている項目を示し、選択された項目の中から指定する0から始まるインデックス。

### contourIndex:

A zero-based index that specifies the contour that contains the handles to move. 
 For paths with multiple contours, the contours are in an arbitrary order.

ハンドルを移動させる曲線を指定する、0から始まるインデックス。複数の曲線パスの場合、曲線は任意の順になります。

### ptToModify:

移動させるハンドルのポイントの位置を指定する、0から始まるインデックス。

### deltaControlPointFirst / deltaControlPointLast:

Points that specify the x,y coordinate values by which the preceding control point and the following control point of ptToModify are moved. For example, passing ({x:1,y:2}) specifies a location that is right by 1 pixel and down by 2 pixels.

X/Y座標を指定するPoint型で、ptToModifyの前のコントロールポイントと次のコントロールポイントが移動されます。例えば、```{ x: 1, y: 2 }```を渡すと、右に1ピクセル・下に2ピクセルの場所を指します。

## 戻り値

なし

## 説明

Moves the specified point’s Bézier handles by a certain amount.

指定されたベジェポイントのハンドルが、一定量で移動します。
