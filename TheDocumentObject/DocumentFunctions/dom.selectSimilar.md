# dom.selectSimilar()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b47.html)

## バージョン

3

## 書式

dom.selectSimilar(tolerance, edgemode, featherAmt, combinemode)

## 引数

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

If Fireworks is in bitmap mode and a pixel selection is active, this function selects all pixels in the current image that are within the specified tolerance of the average color in the current pixel selection.

Fireworksがビットマップモードかつピクセルの選択範囲がある場合、この関数は、既存のピクセル選択範囲の平均色を元に、指定された許容範囲内にあるピクセルを、画像全体の中から選択します。

## 参照

dom.selectSimilarFromPoint()
