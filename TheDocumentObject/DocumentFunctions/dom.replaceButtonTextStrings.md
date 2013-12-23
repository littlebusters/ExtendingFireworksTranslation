# dom.replaceButtonTextStrings()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bd4.html)

## バージョン

3

## 書式

dom.replaceButtonTextStrings(newString, uniformAttrs)

## 引数
     
### newString:

Specifies the string to be used as replacement text.

置換に使うテキストを指定するString型。

### uniformAttrs:

Boolean. If false, each character retains the attributes of the character that was formerly in its position; that is, Fireworks preserves the existing formatting. If true, all characters assume the attributes of the first character in the string that is being replaced.

Boolean型。```false```の場合、各文字は文字の属性を保持しており、Fireworksはそのの書式気を保持します。```true```の場合、すべての文字が置換されるテキストオブジェクトの最初の文字の属性になります。

## 戻り値

なし

## 説明

Replaces all text items (selected and unselected) within the document that are defined as Button Text items with the specified string. (Button Text items are defined as the topmost text items on each frame.)

ボタンテキスト項目として定義されているすべてのテキスト項目（選択・未選択とも）を、指定された文字列で置換します。（ボタンのテキスト項目は、各フレームの一番上のテキスト項目として定義されています）

## 参照

dom.replaceButtonTextStringsInInstances()