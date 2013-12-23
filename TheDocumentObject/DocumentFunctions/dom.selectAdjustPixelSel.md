# dom.selectAdjustPixelSel()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b79.html)

## バージョン

3

## 書式

dom.selectAdjustPixelSel(whatToDo, amount)

## 引数

### whatToDo:

Acceptable values are "expand", "contract", "border", and "smooth".

許容値は、```"expand"``` / ```"contract"``` / ```"border"``` / ```"smooth"```です。

- Use "expand" to expand the pixel selection outward by the number of pixels that are specified by amount.
- Use "contract" to reduce the pixel selection inward by the number of pixels that are specified by amount.
- Use "border" to select a band of pixels the width of amount around the edge of the pixel selection.
- Use "smooth" to smooth out the edge of the pixel selection by amount.

- ```"expand"```は、指定されたピクセル分、選択範囲を外側に拡大します。
- ```"contract"```は、指定されたピクセル分、選択範囲を内側に縮小します。
- ```"border"```は、ビットマップの選択範囲のエッジ周囲を、指定された幅で選択します。
- ```"smooth"```はビットマップの選択範囲のエッジを指定された量で滑らかにします。

### amount:

An integer specifying the amount by which to adjust. Any integer is acceptable.

調整量を指定するInteger型。任意の整数が許容されます。

## 戻り値

なし

## 説明

Expands or reduces the pixel selection by the specified number of pixels, selects a border of pixels, or smooths the edge of the pixel selection.

ビットマップの選択範囲を指定されたピクセル数で拡大または縮小や、ピクセルの選択範囲のエッジを、線または滑らかにします。
