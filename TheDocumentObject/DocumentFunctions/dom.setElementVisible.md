# dom.setElementVisible()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a57.html)

## バージョン

4

## 書式

dom.setElementVisisble(frameIndex, layerIndex, elementIndex, bShow)

## 引数

### frameIndex:

An integer value that specifies the frame that contains the element(s) to be shown or hidden, starting with 0 (although, to specify the current frame, pass –1 here).

表示または非表示させるオブジェクトを含むフレームを指定する、0から始まるInteger型。（現在のフレームを指定するには、-1を渡します）

### layerIndex:

An integer value that specifies the layer that contains the element(s) to be shown or hidden, starting with 0 (although, to specify the current layer, pass –1 here).

表示または非表示させるオブジェクトを含むレイヤーを指定する、0から始まるInteger型。（現在のレイヤーを指定するには、-1を渡します）

### elementIndex:

An integer value that specifies the element(s) to show or hide, starting with 0 (although, to show or hide all the elements in the specified layer, pass –1 here).

表示または非表示させるオブジェクトを指定する、0から始まるInteger型。（指定したレイヤー上のすべてのオブジェクトを、表示または非表示させる場合は、-1を渡します）

### bShow:

Boolean. If true, the element(s) are visible; they are hidden otherwise. 

Boolean型。```true```ならば表示、それ以外は非表示になります。

## 戻り値

なし

## 説明

Shows or hides the specified element(s). 

指定したオブジェクトを表示または非表示にします。

## サンプル

The following command hides all the elements in the current frame and layer:

次のコマンドを実行すると、現在のフレームとレイヤーにあるすべてのオブジェクトを隠します。

```
fw.getDocumentDOM().setElementVisible(-1, -1, -1, false)
```

## 参照

dom.setElementVisibleByName()
