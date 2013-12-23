# dom.setAnimInstanceScaleAmount()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b10.html)

## バージョン

4

## 書式

dom.setAnimInstanceScaleAmount(scaleAmount)

## 引数

### scaleAmount

A positive floating-point value that specifies the amount of scaling to be applied to the animation symbol. For example, pass 50 to scale the symbol to 50% of its current size, and pass 200 to scale it to twice its current size. To specify no scaling, pass 100.

アニメーションシンボルに適用する拡大縮小率を指定するFloat型。例として、```50```を渡した場合、シンボルの現在のサイズを50%にし、```200```を渡した場合、現在のサイズを2倍にします。拡大縮小を指定しない場合は、```100```を渡します。

## 戻り値

なし

## 説明

Sets the scale amount to animate the currently selected animation instance.

現在選択されている要素をアニメーション化し、拡大縮小量を設定します。

## 参照

dom.convertToAnimSymbol()
