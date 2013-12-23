# dom.setElementLockedByName()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a76.html)

## バージョン

8

## 書式

dom.setElementLockedByName(name, bLock)

## 引数

### name:

A string that specifies the name of the element or elements to be locked or unlocked. If more than one element has the same name, the function locks or unlocks all of them.

ロックまたはロックを解除するオブジェクトの生を指定するString型。同じ名前のオブジェクトが複数ある場合、この関数はそのすべてをロックまたはロック解除します。

### bLock:

A Boolean value. If true, the element or elements are locked; if false, they are unlocked.

Boolean型。```true```の場合、オブジェクトをロックし、```false```の場合、ロックを解除します。

## 戻り値

An array of the elements for which the lock status is set.

ロックしたオブジェクトの配列。

## 説明

Locks or unlocks all the elements with the specified name. If no element has the specified name an exception is thrown. If elements are hidden (for example, if they are on a hidden layer or frame), the function will not lock them.

指定した名前のオブジェクトすべてを、ロックまたはロックを解除します。指定した名前のオブジェクトがない場合、例外をスローします。オブジェクトが非表示の場合（例：非表示になっているフレームやレイヤー上にある場合）、この関数はそれらをロックしません。
