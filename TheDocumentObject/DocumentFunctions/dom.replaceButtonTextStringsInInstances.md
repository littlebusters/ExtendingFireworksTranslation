# dom.replaceButtonTextStringsInInstances()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bcd.html)

## バージョン

3

## 書式

dom.replaceButtonTextStringsInInstances(newString, uniformAttrs)

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

Replaces selected button text items with the specified string. (Button text items are defined as the topmost text items on each frame.) 

選択されたボタンのテキスト項目を、指定した文字列で置換します。（ボタンのテキスト項目は、各フレームの一番上のテキスト項目として定義されています）

## 参照

dom.replaceButtonTextStrings()