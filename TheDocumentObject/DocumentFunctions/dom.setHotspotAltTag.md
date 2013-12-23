# dom.setHotspotAltTag()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79e6.html)

## バージョン

3

## 書式

dom.setHotspotAltTag(whatToSet, altTagString)

## 引数

### whatToSet:

Acceptable values are "hotspots", "slices", and "hotspots and slices".

許容された値は、```"hotspots"``` / ```"slices"``` / ```"hotspots and slices"```です。

### altTagString:

A string that specifies the text to be used for the alt tag.

alt属性に使うテキストを指定するString型。

## 戻り値

なし

## 説明

Sets the alt tag text to the specified value for the hotspots and slices in the selection.

選択範囲のスライスとホットスポットのalt属性に指定されたテキストを設定します。

## サンプル

The following command sets the text attributes of the alt tag of the selected slices to “This is my alt tag“:

次のコマンドを実行すると、選択したスライスのalt属性に「This is my alt tag」と設定します。

```
fw.getDocumentDOM().setHotspotAltTag("slices","This is my alt tag");
```