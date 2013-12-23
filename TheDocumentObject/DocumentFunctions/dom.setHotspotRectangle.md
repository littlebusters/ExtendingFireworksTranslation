# dom.setHotspotRectangle()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79df.html)

## バージョン

3

## 書式

dom.setHotspotRectangle(boundingRectangle, bMakeCopy)

## 引数

### boundingRectangle:

A rectangle that specifies the size of the new hotspot or slice (see Rectangle data type).

新しいスライスまたはホットスポットのサイズを指定するRectangle型。（Rectangle型を参照）

### bMakeCopy:

A Boolean value; if it is true, the selection is copied and resized instead of moved and resized.

Boolean型。```true```ならば、選択範囲がコピーされ、サイズが変更される代わりに移動し、リサイズされます。

## 戻り値

なし

## 説明

If the selection is a single hotspot or slice, this function moves or copies it to the specified location at the specified size. 

選択範囲が1つのスライスまたはホットスポットの場合、この関数は指定されたサイズで指定された位置にコピーまたは移動します。