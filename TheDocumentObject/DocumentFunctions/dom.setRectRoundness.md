# dom.setRectRoundness()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7979.html)

## バージョン

4、Fireworks10で修正

## 書式

dom.setRectRoundness(roundness, mode)

## 引数

### roundness:

A floating-point value between 0 and 1 that specifies the roundness to use for the corners (0 is no roundness, 1 is 100% roundness). 

角丸を指定する0から1までのFloat型。（0は角丸なし、1は角丸100%です）

### mode:

String that specifies the mode of corner roundness of the rectangle as either a percentage value or exact pixel value.

パーセントまたはピクセルのいずれかを、角丸のモードとして指定するString型。

## 戻り値

なし

## 説明

Modifies the corner roundness of all the selected rectangle primitives.

選択している矩形の角丸を修正します。

## 参照

dom.addNewRectanglePrimitive(), dom.setRectSides()