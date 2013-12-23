# dom.setLayerVisible()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79a2.html)

## バージョン

3

## 書式

dom.setLayerVisible(layerIndex, frameIndex, bShow, bAllLayers)

## 引数

### layerIndex:

An integer value that specifies the layer that should be shown or hidden, starting with 0 (although, to specify the current layer, pass –1 here). To show or hide all the layers on a frame, use the bAllLayers argument.

表示または非表示するレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定する場合は、-1を渡します）。フレームにあるすべてのレイヤーを表示または非表示にするには、bAllLayers引数を使います。

### frameIndex:

An integer value that specifies the frame that contains the layer to be shown or hidden, starting with 0 (although, to specify the current frame, pass –1 here). A zero-based integer specifying the frame that contains the layer to be shown or hidden.

表示または非表示にするレイヤーを含むフレームを指定する、0から始まるInteger型（現在のレイヤーを指定する場合は、-1を渡します）。0から始まるInteger型は、表示または非表示をするレイヤーを含むフレームを指定します。

### bShow:

Boolean. If true, the layer is visible; if false, the layer is hidden. 

Boolean型。```true```の場合はレイヤーを表示し、```false```の場合はレイヤーを非表示にします。

### bAllLayers:

Boolean. If true, all the layers on the specified frame are shown or hidden, and any value that is passed for layerIndex is ignored. 

Boolean型。```true```の場合は指定したフレームにあるすべてのレイヤーを表示または非表示にし、渡されたlayerIndexの値を無視します。

## 戻り値

なし

## 説明

Shows or hides a layer on the specified frame. 

指定したフレームにあるレイヤーを表示または非表示にします。
