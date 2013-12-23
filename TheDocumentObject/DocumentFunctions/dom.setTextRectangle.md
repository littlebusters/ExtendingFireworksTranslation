# dom.setTextRectangle()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7891.html)

## バージョン

3

## 書式

dom.setTextRectangle(boundingRectangle)

## 引数

### boundingRectangle

A rectangle that specifies the new size within which the text item should flow (see Rectangle data type).

テキストオブジェクトの新しいサイズを指定するRectangle型（Rectangle型を参照）。

## 戻り値

なし

## 説明

Changes the bounding rectangle of the selected text item to the specified size. This function causes the text to reflow inside the new rectangle; the text item is not scaled or transformed. Text that does not fit in the new rectangle is not visible.

選択したテキストオブジェクトの境界を、指定したサイズに変更します。この関数は、新しい矩形内でテキストの送りを変え、テキストオブジェクトは拡大縮小または変形はされません。新しい矩形サイズに収まらないテキストは表示されません。
