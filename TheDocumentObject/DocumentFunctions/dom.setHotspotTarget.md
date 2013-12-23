# dom.setHotspotTarget()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79cc.html)

## バージョン

3

## 書式

dom.setHotspotTarget(whatToSet, targetTagString)

## 引数

### whatToSet:

Acceptable values are "hotspots", "slices", or "hotspots and slices".

許容された値は、```"hotspots"``` / ```"slices"``` / ```"hotspots and slices"```です。

### targetTagString:

A string that specifies the text to be used for the target tag.

target属性で使うテキストを指定するString型。

## 戻り値

なし

## 説明

Sets the target tag text to the specified value for the hotspots and slices in the selection.

選択範囲のスライス・ホットスポットのtarget属性に、指定したテキストを設定します。

## サンプル

The following command links the currently selected slices to the parent window:

次のコマンドを実行すると、現在選択しているスライスのリンクをtargetを親ウィンドウでにします。

```
fw.getDocumentDOM().setHotspotTarget("slices", "_parent");
```
