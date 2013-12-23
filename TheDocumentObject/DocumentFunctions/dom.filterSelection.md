# dom.filterSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d9c.html)

## バージョン

3

## 書式

```
dom.filterSelection(LiveEffect)
```

## 引数

### LiveEffect:

An Effect object (see Effect object).

Effect object型。（Effect object型を参照）

## 戻り値

なし

## 説明

Applies the specified pixel filter to the selection. Items that are not images are converted into images before the filter is applied. Only external filters that are capable of also being Live Effects can be applied using this function. To apply other types of external filters, use dom.filterSelectionByName().

選択範囲に指定されたフィルターを適用します。オブジェクトがビットマップではない場合、フィルタの適用前にビットマップに変換されます。また、ライブエフェクトができる唯一の外部フィルターは、この関数を使用して適用できます。他のタイプの外部フィルターを適用する場合は、```dom.filterSelectionByName()```を使用します。

## サンプル

The following command runs the selected pixels through the hue/saturation filter and then sets hue to 30 and saturation to 20:

次のコマンドは、選択したピクセルに色相30・彩度20で色相・彩度フィルターを実行します。

```
fw.getDocumentDOM().filterSelection({  
	EffectMoaID:"{3439b08d-1922-11d3-9bde00e02910d580}",  
	hls_colorize:true, hue_amount:30, lightness_amount:0, saturation_amount:20  
});
```