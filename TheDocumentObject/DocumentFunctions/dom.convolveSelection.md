# dom.convolveSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e7b.html)

## バージョン

MX 2004

## 書式

```
dom.convolveSelection(kernelWidth, kernelHeight, kernelValues, affectsAlpha)
```

## 引数

### kernelWidth:

An integer that defines the width of the filter coefficients.

フィルタ係数の幅を定義するInteger型。

### kernelHeight:

An integer that defines the height of the filter coefficients.

フィルタ係数の高さを定義するInteger型。

### kernelValues:

An array of integers that defines the values for specific filter patterns.

詳細なフィルタパターン定義する整数値の配列。

### affectsAlpha:

A Boolean value: true means the convolution filter affects the transparency of the bitmap; false means that the bitmap transparency isn’t affected by the filter.

Boolean型。```true```の場合、畳み込みフィルタはビットマップの透明度に影響を与えます。```false```の場合、ビットマップの透明度に影響は与えません。

## 戻り値

なし

## 説明

Applies convolution, or irregular, filters to the selected bitmap based on the pattern defined by the argument values.

引数によって定義されたパターンに基づいて、選択されたビットマップに畳み込みまたは不規則なフィルタを適用します。

## サンプル

The following example applies an edge-detection filter to the bitmap:

次の例では、ビットマップにエッジ検出フィルタを適用します。

```
// width of convolution kernel 
var w = 3;  
// height of convolution kernel 
var h = 3;  
// Edge detection kernel 
var k = new Array(0, 1, 0, 1, -4, 1, 0, 1, 0); 
     
fw.getDocumentDOM().convolveSelection(w, h, k, false);
```