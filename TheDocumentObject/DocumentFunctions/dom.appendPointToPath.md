# dom.appendPointToPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fc7.html)

## バージョン

3

## 書式

```
dom.appendPointtoPath(contourIndex, ptToInsertBefore, controlPointFirst, mainPoint, controlPointLast)
```

## 引数

### contourIndex:

An zero-based index value that specifies the contour to which the Bezier point is appended. For paths with multiple contours, the contours are in an arbitrary order. 

ベジェポイントを追加する輪郭を指定する、0が始まりのインデックス値。複数の輪郭があるパスの場合、輪郭は任意の順になります。

### ptToInsertBefore:

A zero-based index value that specifies where on the path the new point should be placed. The new point is appended in front of the point that this integer represents. To add a point to the beginning of the path, pass 0; to add a point to the end of the path, pass a large number.

追加する新しいパスの場所を指定する、0で始まるインデックス値。この数値で指定されたポイントの前に、新しいポイントが追加されます。パスの先頭にポイントを追加するには0を、パスの末尾にポイントを追加するにはパスの数より大きい値を渡します。

### controlPointFirst / mainPoint / controlPointLast:

Points that specify the x,y coordinates of the preceding control point, the main point, and the following control point of the new point (see Point data type).

新しいポイントの、前アンカーへのポイントハンドル・アンカーポイント・次アンカーへのポイントハンドルのX/Y座標を指定するPoint型。（Point型を参照）

## 戻り値

なし

## 説明

Appends a Bézier point to the selected path.

選択されたパスにベジェポイント：アンカーポイント：を追加します。

## 参照

dom.insertPointInPath()