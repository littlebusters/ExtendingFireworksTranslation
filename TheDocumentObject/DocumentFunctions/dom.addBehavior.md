# dom.addBehavior()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fe7.html)

## バージョン

3

## 書式

```
dom.addBehavior(action, event, eventIndex)
```

## 引数

### action:

"MM_swapImageRestore()"のように、追加するビヘイビアを指定するString型。追加可能なビヘイビアについては、「dom.addBehavior()関数の使用」を参照してください。

### event:

ビヘイビアのトリガーとなるイベント。許容値は、"onMouseOver"、"onMouseOut"、"onLoad"、"onClick".です。

### eventIndex:

ビヘイビアを追加する場所を指定する、0から始まるInteger型。ただし終了位置を指定するには、-1を渡します。

## 戻り値

なし

## 説明

選択されたホットスポットとスライスにビヘイビアを追加します。

## サンプル

次のコマンドは、選択されたホットスポットまたはスライスの終わりに、シンプルロールオーバーのビヘイビアを追加します。

```
fw.getDocumentDOM().addBehavior("MM_simpleRollover()", "onMouseOver", -1);
```

## 参照

dom.removeBehavior()

## 追加情報

Using the dom.addBehavior() function
MM_nbGroup [down]
MM_nbGroup [highlight]
MM_nbGroup [image]
MM_nbGroup [out]
MM_simpleRollover
MM_statusMessage
MM_swapImage
MM_swapImgRestore