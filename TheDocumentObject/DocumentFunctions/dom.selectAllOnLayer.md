# dom.selectAllOnLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7b6d.html)

## バージョン

MX

## 書式

dom.selectAllOnLayer(layerIndex, bRememberSelection, bToggleSelection)

## 引数

### layerIndex:

A long integer that identifies the layer on which to select the element.

要素を選択するレイヤーを識別するInteger型。

### bRememberSelection:

A Boolean value. If true, all the elements on the layer are appended to the current selection.

Boolean型。```true```ならば、レイヤー上のすべての要素を、現在の選択範囲に追加します。

### bToggleSelection:

A Boolean value. Toggles the selection of elements instead of simply selecting them. This parameter is useful only if bRememberSelection is true.

Boolean型。選択しているそれらの要素の代わりに選択範囲を切り替えます。このパラメーターはbRememberSelectionが```true```の時に有効です。

## 戻り値

なし

## 説明

Selects all the items on the given layer in the current frame. This function deselects objects on other layers. If the only element on the layer is a bitmap, Fireworks will enter paint mode on the bitmap.

現在のフレーム内の指定されたレイヤーにあるオブジェクトをすべて選択します。この関数は他のレイヤーにあるオブジェクトの選択を解除します。レイヤーにある要素がビットマップだけだった場合、Fireworksはビットマップモードに入ります。
