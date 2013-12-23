# dom.setTextLeading()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-78c7.html)

## バージョン

MX

## 書式

dom.setTextLeading(leadingValue, leadingMode)

## 引数

### leadingValue:

A floating-point number that determines the spacing between two lines of text. The meaning of leadingValue depends on leadingMode.

テキストの行間を決めるFloat型。leadingValueの解釈は、leadingModeによって変わります。

### leadingMode:

Acceptable values are “exact“ or “percentage“. If set to “exact“, leadingValue is the number of pixels between two lines of text. If set to “percentage“, leadingValue is a percentage of the default leading; 1.0 is the default leading, 0.5 is half the default leading, and 2.0 is double the default leading.

許容される値は、```"exact"``` / ```"percentage"```です。```"exact"```が設定された場合、leadingValueは行間をピクセルにします。```"perentage"```が設定された場合、leadingValuは行間をパーセントに設定します。1.0は標準値で、0.5は標準値の半分、2.0は標準値の2倍になります。

## 戻り値

なし

## 説明

Sets the leading between lines of text. For vertical text mode, the leading is the space between two adjacent columns of text.

テキストの行間を設定します。縦書きの場合、テキストの隣接する列間のスペースを設定します。
