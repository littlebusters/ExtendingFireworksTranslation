# dom.setRectSides()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7972.html)

## バージョン

4

## 書式

dom.setRectSides(newSides)

## 引数

### newSides

A rectangle that specifies the new untransformed sides of the rectangle primitive (see Rectangle data type). Rectangle primitives remember their transformations, so the user sees the transformed result of newSides in the document.

矩形の新しい辺を指定するRectangle型（Rectangle型を参照）。矩形は変形を記憶しており、newSideで変形された結果をドキュメント内表示します。

## 戻り値

なし

## 説明

Modifies the untransformed sides of all selected rectangle primitives.

選択しているすべての矩形の変換されていない辺を修正します。

## 参照

dom.addNewRectanglePrimitive(), dom.setRectRoundnessMode()