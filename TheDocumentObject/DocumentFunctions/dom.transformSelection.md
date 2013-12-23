# dom.transformSelection()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-786a.html)

## バージョン

3、4でアップデート

## 書式

dom.transformSelection(matrix, options)

## 引数

### matrix:

A three-by-three transformation matrix (see Matrix data type).

3×3の変形のMatrix型（Matrix型を参照）

### options:

Acceptable values, some of which were added in Fireworks 4, are "", "transformAttributes", "autoTrimImages", "autoTrimImages transformAttributes", "rememberQuad", "transformAttributes rememberQuad", "autoTrimImages rememberQuad", and "autoTrimImages transformAttributes rememberQuad". 

許容された値（いくつかは Fireworks 4で追加された）は、```""``` / ```"transformAttributes"``` / ```"autoTrimImages"``` / ```"autoTrimImages transformAttributes"``` / ```"rememberQuad"``` / ```"transformAttributes rememberQuad"``` / ```"autoTrimImages rememberQuad"``` / ```"autoTrimImages transformAttributes rememberQuad"```です。

## 戻り値

なし

## 説明

Transforms the selection using the specified three-by-three matrix.

指定された3×3のマトリックスを使って、選択範囲を変形します。
