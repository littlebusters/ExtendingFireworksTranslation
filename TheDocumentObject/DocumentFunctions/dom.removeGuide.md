# dom.removeGuide()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bed.html)

## バージョン

3

## 書式

dom.removeGuide(position, guidekind)

## 引数
     
### position:

A floating-point value that specifies the position of the guide to be removed. 

削除するガイドラインの座標を指定するFloat型。

### guidekind:

Acceptable values are "horizontal" and "vertical". If guidekind is "horizontal", it is assumed that position is a y coordinate; if it is "vertical", it is assumed that position is an x coordinate.

許容値は、```"horizontal"``` / ```"vertical"```。guidekindが```"horizontal"```なら、座標はY座標であると仮定します。```"vertical"```ならば、座標はX座標であると仮定します。

## 戻り値

なし

## 説明

Removes the specified guide. If no guide is at that position, this function has no effect.

指定したガイドを削除します。ガイドが座標にない場合、この関数は効果がありません。
