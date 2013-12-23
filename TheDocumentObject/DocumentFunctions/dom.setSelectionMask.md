# dom.setSelectionMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7f93.html)

## バージョン

4

## 書式

dom.setSelectionMask(mask, howToCombineMasks)

## 引数

### mask:

Specifies the mask to be applied (see Mask data type). If mask is null, an existing pixel-selection mask is removed.

適用するマスクを指定（Mask型を査証）。maskがnullの場合、既存のピクセル選択範囲のマスクは削除されます。

### howToCombineMasks:

If there was previously a mask and mask is not null, howToCombineMasks specifies how the two masks should be combined. Acceptable values are "replace", "add", "subtract", and "intersect".

既存のマスクがあり、maskがnullでない場合、howToCombineMasksは2つのマスクの組み合わせ（演算）方法を指定します。許容値は、"replace" / "add" / "subtract" / "intersect"です。

## 戻り値

なし

## 説明

If Fireworks is in bitmap mode, this function sets the pixel-selection mask of the current image to the specified mask.

Fireworksがビットマップモードの場合、この関数は現在のビットマップのピクセル選択範囲に指定されたマスクを設定します。
