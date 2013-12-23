# dom.getPixelMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d70.html)

## バージョン

3、4以降は非推奨

## 書式

```
dom.getPixelMask()
```

## 引数

なし

## 戻り値

The mask for the current pixel selection. Returns null if Fireworks is not in bitmap mode, or if there is no pixel selection. For information on the format of mask variables, see Mask data type.

ピクセルの選択範囲のためのマスク。```null```が戻り値の場合、Fireworksがビットマップモードになっていないかピクセルの選択範囲がありません。マスクの変数のフォーマットに関しては、Mask型を参照してください。

## 説明

Gets the current pixel-selection mask. The result of this call could be used to call dom.enableElementMask() or dom.enterPaintMode().

現在のビットマップマスクを取得します。この呼び出しの結果は、dom.enableElementMask()またはdom.enterPaintMode()を呼び出すために使用することができます。