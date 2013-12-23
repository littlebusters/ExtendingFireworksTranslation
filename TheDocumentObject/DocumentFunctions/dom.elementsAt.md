# dom.elementsAt()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ddf.html)

## バージョン

MX 2004

## 書式

```
dom.elementsAt(where)
```

## 引数

### where:

Specifies which rectangle to check for elements. To find the elements under a single point (similar to selecting with the Subselection tool), set left equal to right and top equal to bottom. To find elements within a rectangle (similar to drag-selecting with the Pointer tool), set the values to the desired rectangle. 

どちらかで矩形をチェックするか指定します。オブジェクトのシングルポイントを見つけるには、
矩形からオブジェクトを見つけるには、希望するRectangle型を設定します。

## 戻り値

An array of zero of more elements. -> An array of zero or more elements.

0個以上のオブジェクト。

## 説明

Returns a list of zero or more elements at the given location. Similar to selecting with the Subselection tool or drag-selecting with the Pointer tool.

与えられた位置から、0個以上のオブジェクトを配列で返します。ダイレクト選択ツールまたは、選択ツールでのドラッグ選択のように選択した状態に似ています。