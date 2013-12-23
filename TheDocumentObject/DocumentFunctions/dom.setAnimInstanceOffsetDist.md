# dom.setAnimInstanceOffsetDist()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b1e.html)

## バージョン

4

## 書式

dom.setAnimInstanceOffsetDist(offsetDistPt)

## 引数

### offsetDistPt

A point that specifies the distance the animation moves in pixels. For example, passing ({x:100, y:25}) animates the symbol to the right by 100 pixels and 25 pixels down.

アニメーションで動かす距離をピクセルで指定するPoint型。例として、```{x:100, y:25}```を渡すとシンボルは右へ100ピクセル、下へ25ピクセル移動します。

## 戻り値

なし

## 説明

Sets the distance, in pixels, to animate the currently selected animation element.

現在選択されている要素をアニメーション化し、動作距離をピクセルで設定します。

## 参照

dom.convertToAnimSymbol()
