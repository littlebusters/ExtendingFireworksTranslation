# dom.setPageName()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-77de.html)

## バージョン

CS3

## 書式

dom.setPageName(index, name)

## 引数

### index:

An long value that specifies the page number of the page to be renamed.

名前を変更するページナンバーを指定するLong型。

### name:

A string that specifies the new name for the page.

ページの新しい名前を指定するString型。

## 戻り値

なし

## 説明

Renames a page. For example:

ページの名前を変更します。サンプル：

fw.getDocumentDOM().setPageName(0, "new name")