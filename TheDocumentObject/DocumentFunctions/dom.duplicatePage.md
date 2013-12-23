# dom.duplicatePage()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-77ea.html)

## バージョン

CS3

## 書式

```
dom.duplicatePage(pageNum)
```

## 引数

### pageNum:

An long value that specifies the page number of the page to be duplicated.

複製するページのページ番号を指定するlong値。

## 戻り値

なし

## 説明

Duplicates a page. For example:

ページを複製します。例：

```
fw.getDocumentDOM().duplicatePage(1)
```