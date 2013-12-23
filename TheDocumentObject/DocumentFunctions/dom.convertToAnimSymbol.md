# dom.convertToAnimSymbol()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e91.html)

## バージョン

4

## 書式

```
dom.convetToAnimSymbol(name, numFrames, offsetDistPt, rotationAmount, scaleAmount, startOpacity, endOpacity)
```

## 引数

### name:

A string that specifies a name for the new animation symbol.

新しいアニメーションシンボルの名前を指定するString型。

### numFrames:

An integer that specifies the number of frames through which the symbol animates.

シンボルアニメーションのフレーム数を指定するInteger型。

### offsetDistPt:

A point that specifies the distance the animation will move in pixels (see Point data type). For example, passing ({x:100, y:25}) animates the symbol to the right 100 pixels and 25 pixels down.

アニメーションで移動させる距離をpixel単位で指定するPoint型。

### rotationAmount:

A floating-point value that specifies the degrees of rotation to be applied to the animation symbol. For example, passing a value of 720 specifies an animation that does two complete clockwise rotations. To rotate the animation counter-clockwise, pass a negative number.

アニメーションに適用する回転角度を指定するFloat型。例えば、720という値を渡すと、時計回りに2回転します。回転アニメーションを反時計回りにするには、マイナスの数値を渡します。

### scaleAmount:

A positive floating-point value that specifies the amount of scaling to be applied to the animation symbol. For example, passing a value of 50 scales the symbol to 50% of its current size, and passing 200 scales it to twice its current size. To specify no scaling, pass 100.

アニメーションシンボルに適用する拡大縮小率指定するFloat型。例えば、50という値を渡すと現在の大きさを50%にし、200という数値を渡すと2倍の大きさになります。そのままの大きさにするには100を渡します。

### startOpacity / endOpacity:

Float values between 0 and 100 that specify the starting and ending opacity for the animation symbol.

アニメーションシンボルの開始と終了の透明度を指定する、0から100のFloat型。

## 戻り値

なし

## 説明

Converts the selected items to a new animation symbol.

選択したオブジェクトを新しいアニメーションシンボルに変換します。

## 参照

dom.convertAnimSymbolToGraphicSymbol(), dom.convertToSymbol(), dom.setAnimInstanceNumFrames()