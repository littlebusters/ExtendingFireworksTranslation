# dom.selectSimilarFromPoint()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b40.html)

## バージョン

3

## 書式

dom.selectSimilarFromPoint(where, tolerance, edgemode, featherAmt, combinemode)

## 引数

### where:

A point that specifies the x,y coordinates of the pixel whose color is used to calculate the new mask (see Point data type).

新しいマスクを算出するために使う色のピクセルのX/Y座標を指定するPoint型（Pointデータ型を参照）。

### tolerance:

An integer between 0 and 255, inclusive, that specifies the tolerance for selecting pixels.

ピクセルを選択するための許容値を指定する、0から255のInteger型。

### edgemode:

Acceptable values are "hard edge", "antialias", and "feather".

許容値は、```"hard edge"```（アンチエイリアスなし） / ```"antialias"```（アンチエイリアス） / ```"feather"```（ぼかし）です。

### featherAmt:

An integer that specifies the number of pixels to feather. This value is ignored if edgemode is not "feather". 

ぼかし幅のピクセルを指定するInteger型。この値はedgemodeが```"feather"```以外では無視されます。

### combinemode:

Specifies how to combine the new selection mask with the existing mask. Acceptable values are "replace", "add", "subtract", and "intersect".

新しいマスクを既存のマスクに結合する方法を指定します。許容値は、```"replace"``` / ```"add"``` / ```"subtract"``` / ```"intersect"```です。

## 戻り値

なし

## 説明

Behavior is almost identical to dom.selectSimilar(), except that the new mask is calculated from the color at the specified location in the image, rather than from the average color in the selection.

平均色からの選択範囲ではなく、画像の指定された位置のカラーから新しいマスクを算出していることを除いて、dom.selectSimilar()と同じような動作です。

## 参照

dom.selectSimilar()
