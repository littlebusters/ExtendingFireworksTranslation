# dom.addGuide()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7fbd.html)

## バージョン

3

## 書式

```
dom.addGuide(float position, guidekind)
```

## 引数

### float position:

ガイドの追加位置を指定する、XまたはY座標のFloat型（浮動小数点）。

### guidekind:

guidekindで指定できる値は```"horizontal"```と```"vertical"```です。guidekindが```"horizontal"```であればY座標、```"vertical"```ならX座標となります。

## 戻り値

なし

## 説明

ガイドをドキュメントへ追加します。指定された位置にガイドがある場合、この関数は効果がありません。

## サンプル

次のコマンドでは、217のX座標で、垂直のガイドラインを追加します。

```
fw.getDocumentDOM().addGuide(217, "vertical");
```
