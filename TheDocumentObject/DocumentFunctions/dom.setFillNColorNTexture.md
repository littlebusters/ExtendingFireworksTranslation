# dom.setFillNColor()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a24.html)

## バージョン

3

## 書式

dom.setFillNColorNTexture(fill, color, texture-name)

## 引数

### fill:

A Fill object (see Fill object). 

Fill型。

### color:

A color string (see Color string data type).

Color型。

### texture-name:

The name of the texture to be applied.

適用するテクスチャの名前。

## 戻り値

なし

## 説明

Sets the selection to the specified fill, fill color, and fill texture.

指定した選択範囲の塗りに、居ろとテクスチャーを設定します。

## サンプル

The following command sets the selected items to a linear fill with a feather edge and no texture:

次のコマンドを実行すると、選択したオブジェクトに、テクスチャーをなくしエッジをぼかした線グラデーションを設定します。

```
fw.getDocumentDOM().setFillNColorNTexture({ category:"fc_Linear", ditherColors:[ "#000000", "#000000" ], edgeType:"antialiased", feather:10, gradient:{ name:"cn_WhiteBlack", nodes:[ { color:"#ffffff", position:0 }, { color:"#000000", position:1 } ] }, name:"fn_Normal", pattern:null, shape:"linear", stampingMode:"blend opaque", textureBlend:0, webDitherTransparent:false }, "#666666", "Grain");
```
