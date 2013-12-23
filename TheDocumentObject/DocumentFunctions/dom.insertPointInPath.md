# dom.insertPointInPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d14.html)

## バージョン

3

## 書式

dom.insertPointInPath(contourIndex, ptToInsertBefore, tParameter, controlPointFirst, mainPoint, controlPointLast)

## 引数

### contourIndex:

A zero-based index that specifies the contour into which the Bézier point is inserted. For paths with multiple contours, the contours are in an arbitrary order.

ベジェ（アンカー）ポイントを追加する曲線を指定する、0から始まるインデックス。複数の曲線パスの場合、曲線は任意の順になります。

### ptToInsertBefore:

A zero-based index that specifies where the new point should be placed on the path. The new point is appended in front of the point that this integer represents: To add a point to the beginning of the path, pass 0; to add a point to the end of the path, pass a large number.

新しい（アンカー）ポイントのパス上の位置を指定する、0から始まるインデックス。新しいポイントは整数が表すポイントの前に付加されます。パスの先頭にポイントを追加するには0を渡します。パスの終わりにポイントを追加する場合は、最大値を渡します。

### tParameter:

A floating-point value between 0 and 1 that specifies where to insert the new point in the Bézier segment.

ベジェセグメント上のどこに新しいポイントを挿入するかを指定する、0～1の間の浮動小数点値。

### controlPointFirst / mainPoint / controlPointLast:

Points that specify the x,y coordinates of the preceding control point, the main point, and the following control point of the new point (see Point data type).

新しいポイントの、前アンカーへのポイントハンドル・アンカーポイント・次アンカーへのポイントハンドルのX/Y座標を指定するPoint型。（Point型を参照）

## 戻り値

なし

## 説明

Inserts a Bézier point in the selected path. This function is similar to dom.appendPointToPath() but includes a tParameter argument, which lets you control where the point is inserted.

選択したパスにベジェポイントを挿入します。この関数は、dom.appendPointToPath()に似ていますが、tParameter引数が含まれており、これはポイントを挿入する場所をコントロールできます。

## 参照

dom.appendPointToPath()