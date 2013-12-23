# dom.deletePageAt()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-77f8.html)

## バージョン

CS3

## 書式

```
dom.deletePageAt(pageNum)
```

## 引数

### pageNum:

A long value that indicates the page number of the page to be deleted.

削除するページのページ番号を指定するLong型。

## 戻り値

なし

## 説明

Deletes a specified page from the current document.

現在のドキュメントから、指定したページを削除します。

## サンプル

```
fw.getDocumentDOM().deletePageAt(0)
```