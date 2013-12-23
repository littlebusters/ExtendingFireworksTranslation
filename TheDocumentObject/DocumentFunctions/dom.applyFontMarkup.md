# dom.applyFontMarkup()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f1e.html)

## バージョン

3

## 書式

```
dom.applyFontMarkup(fontAttribute, value)
```

## 引数

### fontAttribute:

Acceptable values for fontAttribute are "size" and "face".

fontAttributeの許容値は、```size```と```face```です。

### value:

If fontAttribute is "size", value must be of the form "XXXpt" to specify a point size; a simple numeric value is not allowed.

fontAttributeが```size```の場合、この値はフォントサイズを指定する```XXXpt```の形でなければなりません。数値だけは許可されていません。

## 戻り値

なし

## 説明

Applies the specified font markup attribute to the selected text.

選択しているテキストに、指定されてフォントマークアップの属性を適用します。