# dom.getFontMarkup()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d76.html)

## バージョン

3

## 書式

```
dom.getFontMarkup(fontAttribute)
```

## 引数

### fontAttribute:

Acceptable values for fontAttribute are "size", "color", and "face". 

fontAttributeで許容される値は、```size``` / ```color``` / ```face``` です。

## 戻り値

A string that specifies the markup value. Returns null if the text has multiple attributes or if the selection contains no text. 

指定したマークアップのString型。テキストが複数の属性を持っている場合や、選択範囲にテキストが含まれて居ない場合は、```null```を返します。

## 説明

Gets a font markup attribute for the selected text.

選択したテキストのフォントのマークアップ属性を取得します。