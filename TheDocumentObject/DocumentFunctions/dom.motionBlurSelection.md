# dom.motionBlurSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cc3.html)

## バージョン

MX 2004

## 書式

dom.motionBlurSelection(typeStr, angle, distance, samples)

## 引数

### typeStr:

A string that specifies the type of blur to apply. Valid values are "linear", "radial", and "zoom".

適用するぼかしの種類を指定するStrong型。許容値は、```"linear"``` / ```"radial"``` / ```"zoom"```です。

### angle:

An integer between 0 and 359 that specifies in degrees the direction of the blur, similar to the drop shadow effect angle.

ドロップシャドウ効果の角度と同様に、ぼかしの方向を指定する0から359度のInteger型。

### distance:

A floating-point value between 0 and 400 that specifies in pixels how far from the original image the blur effect will extend.

元の画像からぼかし効果の広がりのピクセル範囲を指定する、0から400までのFloat型。

### samples:

An integer that defines the number of times the original image is cloned and blurred to produce the desired effect.

求められた効果を作るために、元画像のクローンとぼかしの回数を定義するInteger型。

## 戻り値

なし

## 説明

Applies the Motion Blur effect (same as selecting the Filters > Blur > Motion Blur menu option) to the selection.

選択範囲にモーションブラー効果を適用します。（フィルター > ぼかし > モーションブラー メニューオプションと同様）