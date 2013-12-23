# dom.setFillEdgeMode()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a30.html)

## バージョン

3

## 書式

dom.setFillEdgeMode(edgemode, featherAmt)

## 引数

### edgemode:

Acceptable values are "hard edge", "antialias", and "feather".

許容値は、```"hard edge"```（アンチエイリアスなし） / ```"antialias"```（アンチエイリアス） / ```"feather"```（エッジをぼかす）です。

### featherAmt:

An integer that specifies the number of pixels to feather. This value is ignored if edgemode is not "feather".

ぼかし幅を指定するInteger型。edgemodeが```"feather"```ではない場合、この値は無視されます。

## 戻り値

なし

## 説明

Sets the edge type for selected items with fills.

選択したオブジェクトの塗りのエッジを設定します。
