# dom.addNewHotspot()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WSB9487D3F-65B4-42b4-BBEB-B22487F5065D.html)

## バージョン

3

## 書式

```
dom.addNewHotspot(hotspot-kind, hotspot-shape, boundingRectangle)
```

## 引数

### hotspot-kind:

指定できる値は、```"hotspot"```と```"slice"```です。

### hotspot-shape:

指定できる値は、```"rectangle"```と```"oval"```です。

### boundingRectangle:

ホットスポットの範囲（大きさ）を指定するrectangle型。（rectangle型を参照）

## 戻り値

なし

## 説明

指定した範囲に収まる、新しいホットスポットを追加します。

## サンプル

次のコマンドは、指定された座標で矩形スライスを追加します。

```
fw.getDocumentDOM().addNewHotspot("slice","rectangle",{left:0, top:0, right:50, bottom:100});
```