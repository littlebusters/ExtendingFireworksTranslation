# dom.isSelectionDirectlyAboveBitmapObject()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fc3.html)

## バージョン

MX

## 書式

dom.isSelectionDirectlyAboveBitmapObject()

## 引数

なし

## 戻り値

A Boolean value: true if the selected objects are directly above an image element; false otherwise.

Boolean値。選択したオブジェクトが、（レイヤー上で）ビットマップ要素の直接上側にあれば```true```、そうでなければ```false```。

## 説明

Tests to see if the selected object(s) are directly above a bitmap object. The selection does not need to be contiguous, although at least one item in the selection must be directly above a bitmap.

選択したオブジェクト（複数可）が、ビットマップ要素の直接上側にあるかどうかをテストします。選択範囲の少なくとも1つのオブジェクトはビットマップの直接上側にある必要がありますが、連続している必要はありません。