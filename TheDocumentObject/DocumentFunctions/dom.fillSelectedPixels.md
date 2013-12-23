# dom.fillSelectedPixels()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7da3.html)

## バージョン

3

## 書式

```
dom.fillSelectedPixels(clickPt, p1, p2, p3, bFillSelectionOnly, tolerance, edgemode, featherAmt)
```

## 引数

### clickPt:

A point that specifies the x,y coordinates of the pixel to be filled or generated (see Point data type).

塗りまたは生成されるピクセルをX/Y座標で指定するPoint型。

### p1 / p2 / p3:

Points that specify the fill-vector. These arguments are ignored if the current fill does not use a fill-vector.

塗りのベクトルを指定するPoint型。現在の塗りが塗りのベクトルを使用していない場合、この引数は無視されます。

### bFillSelectionOnly:

If bFillSelectionOnly is true, the remaining arguments are ignored. If it is false, the current pixel selection is ignored, and a new one is generated using the values passed for tolerance, edgemode, and featherAmt. (This behavior is the same as if the Magic Wand tool were used at the clickPt location.)

bFillSelectionOnlyが```true```の場合、残りの引数が無視されます。```false```の場合、現在のピクセル選択範囲が無視され、	新しく tolerance / edgemode / featherAmt に渡された値を使用して生成されます。

### tolerance:

An integer between 0 and 255, inclusive, that specifies the tolerance for selecting pixels.

選択するピクセルの許容量を指定する、0から255のInteger型。

### edgemode:

Acceptable values are "hard edge", "antialias", and "feather".

許容される値は、```hard edge```（アンチエイリアスなし） / ```antialias```（アンチエイリアス） / ```feather```（ぼかし） です。

### featherAmt:

An integer between 0 and 32,000, inclusive, that specifies the number of pixels to feather. This value is ignored if the value of edgemode is not "feather". 

ぼかし幅を指定する、0から32,000のInteger型。edgemodeが```feather```でない場合、この値は無視されます。

## 戻り値

なし

## 説明

When the selection is an image and Fireworks is in bitmap mode, this method fills the selected pixels with the current fill or generates a new pixel selection.

Fireworksがビットマップモードかつビットマップを選択している時、選択している範囲を現在の塗りにするか、選択範囲に新しいピクセルを生成します。

## サンプル

The following command fills the selection with a hard edge, and the tolerance set to 32:

次のコマンドを実行すると、選択範囲をアンチエイリアスなし、許容量を32で塗りつぶします。

```
fw.getDocumentDOM().fillSelectedPixels({x:207, y:199}, {x:207, y:199}, {x:207, y:199}, {x:207, y:199}, false, 32, "hard edge", 0);
```