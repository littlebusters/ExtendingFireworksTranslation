# dom.convertPathToMarquee()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e97.html)

## バージョン

7

## 書式

```
dom.convertPathToMarquee(mode, featherAmount)
```

## 引数

### mode:

Sets the mode. Acceptable values are "hard edge", "antialias", and "feather".

モードを設定します。許容値は、```hard edge```（アンチエイリアスなし） / ```antialias```（アンチエイリアス） / ```feather```（ぼかし）です。

### featherAmount:

Sets the amount of feathering for the marquee selection. This value is ignored if mode is not set to "feather"

選択範囲のぼかし量を設定します。modeが```feather```ではない場合、この値は無視されます。

## 戻り値

なし

## 説明

Converts path to marquee selection.

パスを選択範囲に変換します。