# dom.setAnimInstanceRotationAmount()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b17.html)

## バージョン

4

## 書式

dom.setAnimInstanceRotationAmount(rotationAmount)

## 引数

### rotationAmount

A floating-point value that specifies the degree of rotation to be applied to the animation symbol. For example, passing 720 specifies an animation that does two complete clockwise rotations. To rotate the animation counter-clockwise, pass a negative number.

アニメーションシンボルに適用する回転角度を指定するFloat型。例として、```720```を渡した場合のアニメーションは、時計回りに2回転します。反時計回りにアニメーションさせるには、負の数値を渡します。

## 戻り値

なし

## 説明

Sets the rotation amount, in degrees, to animate the currently selected animation element.

現在選択されている要素をアニメーション化し、回転量を角度で設定します。

## 参照

dom.convertToAnimSymbol()
