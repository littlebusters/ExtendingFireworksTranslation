# dom.linkElementMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cee.html)

## バージョン

4

## 書式

dom.linkElementMask(frame, layer, element, bLink)

## 引数

### frame:

An integer value that specifies the frame that contains the element, starting with 0 (although, to specify the current frame, pass –1 here).

要素が含まれているフレームを指定する、0から始まるInteger型（現在のフレームを指定するには-1を渡します）。

### layer:

An integer value that specifies the layer that contains the element, starting with 0 (although, to specify the current layer, pass –1 here).

要素が含まれているレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定するには-1を渡します）。

### element:

An integer value that specifies the element, starting with 0 (although, to specify the current element, pass –1 here).

要素を指定する、0から始まるInteger型（現在の要素を指定するには-1を渡します）。

### bLink:

If bLink is true, the element masks are linked to their elements; if false, they are unlinked from their elements.

bLinkが```true```ならば、マスクはそれらの要素にリンクし、```false```ならばそれらの要素からリンクを解除します。

## 戻り値

なし

## 説明

Links or unlinks the element mask on the selected element. If more than one element (or no elements) are selected when this function is called, Fireworks throws an exception. An exception is also thrown if the element has no element mask.

選択したオブジェクトのマスクのリンクまたはリンク解除をします。この関数が呼び出されたときに、複数の要素（または要素なし）を選択している場合、Fireworksは例外をスローします。オブジェクトがマスクを持っていない場合も例外をスローします。