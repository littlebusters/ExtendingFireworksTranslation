# dom.setElementVisible()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a4f.html)

## バージョン

4

## 書式

dom.setElementVisibleByName(name, bShow)

## 引数

### name:

A string that specifies the name of the element(s) to be shown or hidden. If more than one element has the same name, this function shows or hides all of them.

表示または隠すオブジェクトの名前を指定するString型。複数の同じ名前があった場合、この関数はすべてのオブジェクトを表示または隠します。

### bShow:

Boolean. If true, the elements are visible; they are hidden otherwise. 

Boolean型。```true```ならば、オブジェクトを表示し、それ以外は隠します。

## 戻り値

An array of the elements for which visibility was set. 

可視属性を設定したオブジェクトの配列。

## 説明

Shows or hides all the elements with the specified name. If no element has the specified name, an exception is thrown. If the elements are hidden because they are on a hidden layer or frame, for example, this function does not show them.

指定した名前のすべてのオブジェクトを、表示または隠します。指定した名前のオブジェクトがない場合、例外をスローします。また隠されたフレームまたはレイヤーにあるオブジェクトはこの関数では表示されません。

## 参照

dom.findNamedElements(), dom.setElementName(), dom.setElementVisible()
