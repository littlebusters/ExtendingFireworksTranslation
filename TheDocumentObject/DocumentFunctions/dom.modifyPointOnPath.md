# dom.modifyPointOnPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ccf.html)

## バージョン

3

## 書式

dom.modifyPointOnPath(ontourIndex, ptToModify, controlPointFirst, mainPoint, controlPointLast, dReapplyAttrs, bClosePath)

## 引数

### ontourIndex:

A zero-based index that specifies the contour into which the Bézier point is inserted. For paths with multiple contours, the contours are in an arbitrary order.

ベジェ（アンカー）ポイントを追加する曲線を指定する、0から始まるインデックス。複数の曲線パスの場合、曲線は任意の順になります。

### ptToModify:

A zero-based index that specifies the point to be modified.

変更する（アンカー）ポイントのパス上の位置を指定する、0から始まるインデックス。

### controlPointFirst / mainPoint / controlPointLast:

Points that specify the x,y coordinates of the preceding control point, the main point, and the following control point of the new point (see Point data type). 

新しいポイントの、前アンカーへのポイントハンドル・アンカーポイント・次アンカーへのポイントハンドルのX/Y座標を指定するPoint型。（Point型を参照）

### dReapplyAttrs:

If dReapplyAttrs is true, the path has the document’s current fill, stroke, and so on reapplied to it. If it is false, the path attributes are not changed.

dReapplyAttrが```true```ならば、ドキュメントの塗り・線がパスに再適用されます。```false```の場合、パスの属性は変更されません。

### bClosePath:

If bClosePath is true, the path is marked as closed after modifying the point. If it is false, the path retains its original open or closed value.

bClosePathが```true```の場合、ポイントの変更後、クローズパスとなります。```false```の場合、元の属性（オープンパス/クローズパス）を保持します。

## 戻り値

なし

## 説明

Modifies an existing point on the selected path.

選択したパス上のポイントを変更します。