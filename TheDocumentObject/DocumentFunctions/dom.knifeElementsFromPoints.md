# dom.knifeElementsFromPoints()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cee.html)

## バージョン

3

## 書式

dom.knifeElementsFromPoints(from, to, tolerance)

## 引数

### from:

A point that specifies the x,y coordinates of the point where the user clicked and started to drag (see Point data type). 

ユーザーがクリックとドラッグをスタートしたポイントを指定する、X/Y座標のPoint型（Point型を参照）。

### to:

A point that specifies the x,y coordinates of the point where the user ended the drag operation.

ユーザーがドラッグを終了したポイントを指定する、X/Y座標のPoint型（Point型を参照）。

### tolerance:

A floating-point value > = 0 that specifies the tolerance within which items are cut.

オブジェクトがカットされる許容範囲を指定する、0以上のFloat型。

## 戻り値

true if anything is cut; false otherwise.

いずれかがカットできれば```true```、そうでなければ```false```。

## 説明

When the user clicks a single point while using the Knife tool, this function cuts paths within the specified tolerance. This action is similar to using the Knife tool with a single click.

When the user drags while using the Knife tool, this function cuts additional items within the specified tolerance. This action is similar to using the Knife tool with a drag operation.

ナイフツールを使用している間、ユーザーがドラッグすると、この関数で指定された許容範囲内でパスを切ります。このアクションは、ドラッグ操作でナイフツールを使用するのと同様です。

## 参照

dom.knifeElementsFromPoint()