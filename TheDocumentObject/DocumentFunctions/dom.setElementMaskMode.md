# dom.setElementMaskMode()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7a6a.html)

## バージョン

4

## 書式

dom.setElementMaskMode(mode)

## 引数

### mode:

Acceptable values are "mask to image" and "mask to path". 

許容値は、```"mask to image"``` / ```"mask to path"```です。

## 戻り値

なし

## 説明

Sets the rendering mode on the selected element’s element mask. Only one element can be selected when calling this function. If more than one element (or no elements) are selected when this function is called, Fireworks throws an exception. Fireworks also returns an error if the selected element has no element mask.

選択したオブジェクトのマスクのレンダリングモードを設定します。この関数は、オブジェクトを1つだけ選択している時に呼び出せます。多数のオブジェクトを選択して（またはオブジェクトの選択がない）関数を呼び出した場合、Fireworksは例外をスローします。選択したオブジェクトにマスクがない場合も、Fireworksはエラーを返します。
