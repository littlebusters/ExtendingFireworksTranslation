# dom.setTextRectangleAutoFromPoint()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7884.html)

## バージョン

3

## 書式

dom.setTextRectangleAutoFromPoint(anchorPoint)

## 引数

### anchorPoint:

A point that specifies the x,y coordinates of the location at which the text box should be anchored (see Point data type). How the point is used depends on the left-to-right and up-to-down orientation of the text flow in the text block.

テキストオブジェクトを固定する位置のX / Y座標を指定するPoint型。Point型の使用方法は、テキストブロックの揃えleft-to-rightとup-to-downの配向に依存します。

* Left-justified horizontal text is placed with its top and left edges at anchorPoint, and the text expands to the right.
* Centered horizontal text is centered horizontally around anchorPoint and expands equally to the left and right.
* Centered vertical text is centered vertically around anchorPoint and expands equally up and down.

* 左両端ぞろえの水平方向のテキストは、左上をアンカーポイントとし、テキストは右方向に展開されます。
* 中央揃えの水平方向のテキストは、水平方向の中央がアンカーポイントとなり、左右均等に展開されます。
* 中央揃えの垂直方向のテキストは、垂直方向の中央がアンカーポイントとなり、上下均等に展開されます。

## 戻り値

なし

## 説明

Performs the same function as dom.setTextRectangleAuto(), but lets you pass a point to specify where the rectangle should be located.

dom.setTextRectangleAuto()と同じような機能の関数ですが、Pointを渡すことで、矩形を配置する場所を指定することができます。

## 参照

dom.setTextRectangleAuto()
