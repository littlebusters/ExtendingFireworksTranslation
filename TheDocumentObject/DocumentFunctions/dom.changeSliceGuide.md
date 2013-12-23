# dom.changeSliceGuide()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7efc.html)

## バージョン

MX

## 書式

```
dom.changeSliceGuide(currentPosition, newPosition, guidekind, isMagneticDrag, isSingleDrag)
```

## 引数

### currentPosition:

A floating-point value that specifies the current position of the slice guide to be moved. 

移動させるスライスガイドの現在位置を指定するFloat型。

### newPosition:

A floating-point value that specifies the new position of the slice guide.

スライスガイドの新しい位置を指定するFloat型。

### guidekind:

Acceptable values are "horizontal" and "vertical". If the value of guidekind is “horizontal” , Fireworks assumes that the specified positions are y coordinates; if "vertical", the specified positions are x coordinates.

guidekindの許容値は、```horizontal```と```vertical```です。guidekindが```horizontal```の場合、指定された位置はY座標になります。guidekingが```vertical```の場合、指定された位置はX座標になります。

### isMagneticDrag:

A Boolean value that determines whether to move other slice guides between the old and new positions. If isMagneticDrag is true, Fireworks also moves slice guides between the old guide position and the new position. This action resizes and possibly deletes rectangular slices that do not abut the slice guide at currentPosition.

現在の位置と新しい値の間にある、他のスライスガイドも移動させるのかを指定するBoolean値。isMagneticDragが　```true```の場合、Fireworksは古い位置と新しい位置の間にあるスライスガイドをを移動します。このアクションは矩形スライスのサイズを変更し、現在の位置にスライスガイドが当接しない時は、スライスガイドが削除されます。

### isSingleDrag:

A Boolean value that determines whether the operation is performed only on the selected slice or on all slices that are affected by the slice guide. If isSingleDrag is true, Fireworks performs only the changeSliceGuide() action on the selected slice.

操作を選択したスライスのみに行うのか、すべてのスライスに対して行うのかを設定する、Boolean値。isSingleDragが```true```の場合、Fireworksは選択しているスライスにのみ changeSliceGuide（）を実行します。

## 戻り値

なし

## 説明

Moves a slice guide’s position to a new location, which resizes any rectangular slices that abut the guide. An argument controls whether slice guides that exist between the old position and the new one are also moved.

スライスガイドを新しい値へ移動し、矩形スライスのサイズを変更します。古い位置と新しい位置の配置されているスライスガイドを移動させるかどうかを、引数で指定します。

If a slice is resized so that it has zero width or height, the slice is deleted.

サイズ変更により、スライスの幅 / 高さが0になった場合、そのスライスは削除されます。

This function does not change slices that are not rectangular.

この関数は矩形以外のスライスは変更しません。

## サンプル

The following command moves a vertical slice guide from position 135 to position 275, and moves all vertical slice guides between 135 and 275 to 275:

次のコマンドは、X座標にあるスライスガイドを135から275へ移動し、その間にあるすべてのX座標ガイドラインを移動します。

```
fw.getDocumentDOM().changeGuide(135, 275, "vertical", true);
```