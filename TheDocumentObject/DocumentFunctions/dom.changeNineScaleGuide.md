# dom.changeNineScaleGuide()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-784b.html)

## バージョン

CS3

## 書式

```
dom.changeNineScaleGuide(oldpos, newpos, guidekind)
```

## 引数

### oldpos:

A double precision value that specifies the current position of the guide.

ガイドラインの現在の位置を指定するDouble型

### newpos:

A double precision value that specifies the new position of the guide.

ガイドラインの新しい位置を指定するDouble型

### guidekind:

Acceptable values for guidekind are "horizontal" and "vertical". If guidekind is "horizontal", it is assumed that the specified positions are y coordinates; if guidekind is "vertical", it is assumed that the specified positions are x coordinates.

guidekindの許容値は、```horizontal```と```vertical```です。guidekindが```horizontal```の場合、指定された位置はY座標になります。guidekingが```vertical```の場合、指定された位置はX座標になります。

Returns

## 戻り値

なし

## 説明

Moves a 9-slice scaling guide’s position to a new location.

9スライスガイドを新しい位置に移動します。

## サンプル

The following command moves a vertical guide from position 135 to position 275:

次のコマンドは、X座標にあるガイドラインを135から275へ移動します。

```
fw.getDocumentDOM().changeNineScaleGuide(135, 275, "vertical");
```