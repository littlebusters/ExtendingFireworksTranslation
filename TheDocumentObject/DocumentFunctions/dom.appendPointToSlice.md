# dom.appendPointToSlice()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f38.html)

## バージョン

3

## 書式

```
dom.appendPointToSlice(pt, tolerance)
```

## 引数

### pt:

A point that specifies the x,y coordinates of the point to be added (see Point data type).

追加するポイントのX/Y座標を指定するPoint型。（Point型を参照）

### tolerance:

A floating-point value > = 0 that specifies the tolerance between the new point and the starting point of the polyline path. If the new point is within tolerance of the starting point, the polyline path is closed.

多角形パスの新しい：アンカー：ポイントと開始：アンカー：ポイントの許容値を指定する0以上のFloat型。新しいポイントが開始ポイントの許容内であれば、多角形パスは閉じられます。

## 戻り値

なし

## 説明

Appends a point to the selected unclosed polygon hotspot. If an unclosed polygon hotspot is not selected, a new polygon hotspot is created with the single point that passed in.

選択された閉じられていない多角形スライスに新しいポイントを追加します。閉じられていない多角形スライスが選択されていない場合、新しい多角形スライスが、シングルポイントとして作成されます。