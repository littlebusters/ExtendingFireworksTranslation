# dom.setPixelMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7995.html)

## バージョン

3、4でdom.setSelectionMask()に変更し廃止

## 書式

dom.setPixelMask(mask, howToCombineMasks)

## 引数

### mask:

A mask variable that specifies the mask to be applied (see Mask data type). If mask is null, any existing pixel-selection mask is removed. 

適用するマスクを指定するMask型。maskがnullの場合、既存のビットマップマスクは削除されます。

### howToCombineMasks:

If there was previously a mask and the new mask is also not null, then howToCombineMasks specifies how the two masks should be combined. Acceptable values for howToCombineMasks are "replace", "add", "subtract", and "intersect".

以前あったマスクも新しいマスクもnullでない場合、howToCombineMasksは2つのマスクの組み合わせ方法を指定します。howToCombineMasksで許容される値は、```"replace"``` / ```"add"``` / ```"subtract"``` / ```"intersect"```です。

## 戻り値

なし

## 説明

If Fireworks is in bitmap mode, this function sets the pixel-selection mask of the current image to the specified mask.

Fireworksがビットマップモードで、この関数を実行すると、指定されたマスクで現在のビットマップの選択範囲にマスクを設定します。

## 参照

dom.setSelectionMask()
