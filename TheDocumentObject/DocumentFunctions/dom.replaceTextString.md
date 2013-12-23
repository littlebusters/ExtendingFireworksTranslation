# dom.replaceTextString()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bc6.html)

## バージョン

3

## 書式

dom.replaceTextString(newString, uniformAttrs)

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

Replaces the text of all selected text items with the specified string. 

選択されたテキストオブジェクトのテキストを、指定された文字列で置換します。
