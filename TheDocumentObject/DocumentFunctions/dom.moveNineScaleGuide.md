# dom.moveNineScaleGuide()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS4539F8C4-E027-48d3-B43A-F3F8B5C0E52F.html)

## バージョン

10

## 書式

dom.moveNineScaleGuide(delta, guidekind)

## 引数

### delta:

A point that specifies the values by which the 9-slice scaling guide is moved. 

移動させる9スライスガイドの距離を指定するPoint型。

### guidekind:

Direction in which the 9-slice scaling guide is moved.

移動させる9スライスガイドを指定します。

## 戻り値

なし

## 説明

Moves a 9-slice scaling guide’s position by specified pixels. Acceptable values for guidekind are "horizontal-top", “horizontal-bottom”, “vertical-left” and “vertical-right”. If guidekind is “horizontal”, it is assumed that the specified positions are y coordinates; if it is “vertical”, it is assumed that the specified positions are x coordinates.

9スライスガイドを移動させる位置をピクセル数で指定します。許容されるguidekindの値は、```"horizontal-top"``` / ```“horizontal-bottom”``` / ```“vertical-left”``` / ```“vertical-right”```です。guidekindが```"horizontal"```の場合、Y座標を指定したものとします。guidekindが```"vertical"```の場合、X座標を指定したものとします。

## 例

The following command moves a horizontal top guide by 10 pixels.

次のコマンドを実行すると、水平上部のガイドを10ピクセル移動させます。

```
fw.getDocumentDOM().moveNineScaleGuide("horizontal-top",10);
```