# dom.duplicateLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e06.html)

## バージョン

3

## 書式

```
dom.duplicateLayer(layerIndex, {howMany}, {where})
```

## 引数

### layerIndex:

An integer value that specifies the layer to duplicate, starting with 0 (although, to specify the current layer, pass –1 here).

0から始まる、複製するレイヤーを指定するInteger型。

### howMany [optional]:

An optional integer that specifies how many times to duplicate the layer. If omitted, the layer is duplicated once. 

複製するレイヤー数を指定するオプションのInteger型。省略した場合は、レイヤーは1つ複製されます。

### where [optional]:

An optional argument that specifies where to put the new layer(s) in relation to the source layer. Acceptable values are "beginning", "before current", "after current", and "end". If omitted, "before current" is assumed.

新しいレイヤーの位置を指定するオプションの引数。許容値は、```beginning```（一番上に挿入） / ```before current```（現在のステートの前に挿入） / ```after current```（現在のステートの後に挿入） / ```end```(一番下に挿入)です。省略された場合、```before current```となります。

## 戻り値

なし

## 説明

Duplicates a layer.

レイヤーを複製します。

## サンプル

The following command places three copies of the current layer at the end of the document:

次のコマンドを実行すると、現在のレイヤーを3つ複製し、一番下に配置します。

```
fw.getDocumentDOM().duplicateLayer(-1, 3, "end");
```