# dom.setElementLocked()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a76.html)

## バージョン

8

## 書式

dom.setElementLocked(frameNum, layerNum, objectIndex, bLock, bAllLayers, bLockLayers)

## 引数

### frameNum:

A zero-based integer that specifies the frame that contains the element or elements to be locked. To specify the current frame, pass -1.

ロックするオブジェクトを含むフレームを指定する、0から始まるInteger型。現在のフレームを指定するには-1を渡します。

### layerNum:

A zero-based integer that specifies the layer that contains the element or elements to be locked. To specify the current layer, pass -1.

ロックするオブジェクトが含まれるレイヤーを指定する、0から始まるInteger型。現在のレイヤーを指定するには-1を渡します。

### objectIndex:

A zero-based integer that specifies the element or elements to lock or unlock. 0 represents the topmost element in the specified layer. To lock or unlock all the elements in the specified layer, pass -1.

ロックまたはロック解除をするオブジェクトを指定する、0から始まるInteger型。0は指定したレイヤー上で一番上にあるオブジェクトを意味します。指定したレイヤー上で、すべてのオブジェクトのロックまたはロック解除をする場合、-1を渡します。

### bLock:

A Boolean value. If true, the element or elements are to be locked; if false, the elements are unlocked.

Boolean型。```true```の場合、オブジェクトをロックし、```false```の場合、オブジェクトのロックを解除します。

### bAllLayers:

A Boolean value. If true, all layers are specified; false otherwise.

Boolean型。```true```の場合、すべてのレイヤーを指定し、```false```はそれ以外となります。

### bLockLayers:

A Boolean value. If true, locks all layers; false otherwise.

Boolean型。```true```の場合、すべてのレイヤーをロックし、```false```はそれ以外となります。

## 戻り値

なし

## 説明

Sets the name of the selected element or elements.


