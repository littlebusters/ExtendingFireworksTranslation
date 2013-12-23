# dom.scaleSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b80.html)

## バージョン

3

## 書式

dom.scaleSelection(xScaleAmount, yScaleAmount, opts)

## 引数

### xScaleAmount / yScaleAmount:

Float values that specify the amount to scale the selection in the horizontal and vertical axes. Acceptable values are 0.0 or greater; a value of 1 represents 100%, 2 represents 200%, and so on.

選択範囲をスケールする水平垂直の量を指定するFloat型。許容値は0.0以上で、1は100%を表し、2は200%を表します。

### opts:

Acceptable values are "transformAttributes", "autoTrimImages", and “autoTrimImages transformAttributes“.

許容値は、```"transformAttributes"``` / ```"autoTrimImages"``` / ```“autoTrimImages transformAttributes“```です。

## 戻り値

なし

## 説明

Scales the selection in the horizontal and vertical axes.

水平垂直に選択範囲をスケールします。

## サンプル

The following command scales the selected items to approximately two-thirds (67%) and automatically trims the images and transforms the attributes:

次のコマンドを実行すると、選択したオブジェクトを2/3（約67%）にスケールし、ビットマップの切り取りと属性の変形します。

```
fw.getDocumentDOM().scaleSelection(0.67, 0.67, "autoTrimImages transformAttributes");
```
