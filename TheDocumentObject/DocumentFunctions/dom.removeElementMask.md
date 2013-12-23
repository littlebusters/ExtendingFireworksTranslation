# dom.removeElementMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7bff.html)

## バージョン

4

## 書式

dom.removeElementMask(whatIfElementIsAnImage)

## 引数
     
### whatIfElementIsAnImage:

This argument is used only if the element (not the element mask) is an image. Acceptable values are "apply" (apply the element mask to the image before discarding the element mask), "discard" (discard the element mask), and "ask" (displays a dialog box to let the user decide). If you pass "ask" and the user cancels the dialog box, Fireworks returns an error.

この引数は要素が画像（マスクではない）の場合のみ使用されます。許容値は、```"apply"```（マスクを削除する前に、画像にマスクを適用） / ```"discard"```（マスクを削除） / ```"ask"```（ダイアログを表示しユーザーが選択）です。もし、```"ask"```を渡し、ユーザーがダイアログをキャンセルすると、Fireworksはエラーを返します。

## 戻り値

なし

## 説明

Removes the mask from the selected element. If more than one element (or no elements) are selected when this function is called, Fireworks throws an exception.

選択した要素のマスクを削除します。この関数を呼び出したときに、複数の要素が選択（または要素の選択がない）場合、Fireworksは例外をスローします。