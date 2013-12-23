# dom.setHotspotColor()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79df.html)

## バージョン

3

## 書式

dom.setHotSpotColor(whatToSet, color)

## 引数

### whatToSet:

Acceptable values are "hotspots", "slices", and "hotspots and slices".

許容された値は、```"hotspots"``` / ```"slices"``` / ```"hotspots and slices"```です。

### color:

A color string (see Color string data type).

ColorString型。（ColorString型を参照）

## 戻り値

なし

## 説明

Sets the color to the specified value for the hotspots and slices in the selection.

選択したスライスとホットスポットを指定された色に設定します。

## サンプル

The following command sets the color of the selected hotspots to red:

次のコマンドを実行すると、選択したホットスポットの色を赤に設定します。

```
fw.getDocumentDOM().setHotspotColor("hotspots", "#ff0000");
```