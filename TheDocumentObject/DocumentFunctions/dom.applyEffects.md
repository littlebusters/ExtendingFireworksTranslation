# dom.applyEffects()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f25.html)

## バージョン

3

## 書式

```
dom.ApplyEffects(effectList)
```

## 引数

### effectList:

An EffectList object (see EffectList object). If effectList is null, this function removes all effects from the selection.

EffectList型。effectListが```null```の場合、この関数は選択範囲からすべてのフィルターを削除します。（EffectList型を参照）

## 戻り値

なし

## 説明

Applies the specified effects to the selection.

選択範囲に指定されたフィルターを適用します。

## サンプル

The following command applies a drop shadow with an angle of 315, a blur of 4, a color of black, and a distance of 7 (see Drop Shadow object):

次のコマンドは、選択範囲に角度：315°・ぼかし：4・カラー：黒・距離：7のドロップシャドウを適用します。（Drop Shadowオブジェクトを参照）

```
fw.getDocumentDOM().applyEffects({category:"Untitled", effects:[ { EffectIsVisible:true, EffectMoaID:"{a7944db8-6ce2-11d1-8c76000502701850}", ShadowAngle:315, ShadowBlur:4, ShadowColor:"#000000a6", ShadowDistance:7, ShadowType:0, category:"Shadow and Glow", name:"Drop Shadow" } ], name:"Untitled" });
```