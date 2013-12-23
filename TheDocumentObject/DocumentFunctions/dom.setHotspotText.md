# dom.setHotspotText()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79c5.html)

## バージョン

3

## 書式

dom.setHotspotText(whatToSet, textString, urlToMatch, bUpdateAttributes)

## 引数

### whatToSet:

Acceptable values are "hotspots", "slices", or "hotspots and slices".

許容された値は、```"hotspots"``` / ```"slices"``` / ```"hotspots and slices"```です。

### textString:

A string that specifies the text to be used for the hotspot or slice.

スライスまたはホットスポットで使うテキストを指定するString型。

### urlToMatch:

A string that specifies a URL that is already assigned to one or more hotspots in the document. If this value is not null, the URLs of all hotspots or slices in the document that have urlToMatch as their URL are changed to textString. 

すでにドキュメント内で、1つまたは複数のホットスポットに割り当てられているURLを指定するString型。この値がnull以外の場合、URLとしてurlToMatchの値を持つドキュメント内のスライス・ホットスポットのURLは、textStringに変更されます。

#### Note: The URLs of both selected and unselected hotspots or slices are changed.

選択・未選択両方のスライスとホットスポットのURLが変更されます。

### bUpdateAttributes:

Boolean. If true, changed hotspots inherit the color, target, and alt tag text that were most recently associated with the new text value. For example, suppose textString is "http://www.mywebsite.com", and the last time "http://www.mywebsite.com" was used, it was used with a color of blue, a target of none, and an alt tag of “Link to My Home Page”. If bUpdateAttributes is true, any hotspot or slice whose text is now being changed to "http://www.mywebsite.com" will also have a color of blue, a target of none, and an alt tag text of "Link to My Home Page".

Boolean型。```true```の場合、変更のあったホットスポットの色・ターゲット・alt属性は、新しく関連付けられていた値を継承します。例として、textStringが"http://www.mywebsite.com"で、"http://www.mywebsite.com"が最後に使用した設定が、色は青、ターゲットはなし、alt属性は“Link to My Home Page”だったと想定します。bUpdateAttributesが```true```だった場合、複数のスライスやホットスポットの文字が"http://www.mywebsite.com"になったとしても、色は青、ターゲットはなし、alt属性は"Link to My Home Page"です。

## 戻り値

なし

## 説明

Sets the hotspot text to the specified value for the hotspots and slices in the selection. 

選択範囲のスライスとスポットのホットスポットテキストを指定された値に設定します。

## サンプル

The following command creates a slice and inserts the HTML text, "I am HTML text":

次のコマンドを実行すると、スライスを生成しHTMLテキストとして"I am HTML text"を挿入します。

```
fw.getDocumentDOM().setHotspotText("Slice ","I am HTML text", null, true);
```
