# dom.group()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7f86.html)

## バージョン

3、4よりアップデート

## 書式

```
dom.hasCharacterMarkup(tag)
```

## 引数

### tag:

Acceptable values are "b", "i", and "u", for bold, italic, and underline; and "fwplain", which was added in Fireworks 4, for text without character markup.

許容値は、```b``` / ```i``` / ```u```で、太字・斜体・下線と、```fwplain```で、これは文字の修飾がないテキストとして、Fireworks 4から追加されました。

## 戻り値

true if the text has the specified character markup; false if it does not or if only part of the text has the markup.

```true```の場合、テキストに指定された修飾が指定されています。```false```の場合、修飾がないかテキストの一部が修飾されています。

## 説明

Determines whether the selected text has the specified character markup.

選択したテキストに指定した就職があるかどうかを調べます。