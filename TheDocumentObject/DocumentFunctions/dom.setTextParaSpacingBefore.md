# dom.setTextParaSpacingBefore()()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-78a3.html)

## バージョン

MX

## 書式

dom.setTextParaSpacingBefore(paraSpaceBefore)

## 引数

### paraSpaceBefore

The number of pixels to move down before starting a new paragraph.

段落の前にピクセルを入れ、次の段落のスタート位置をずらします。

## 戻り値

なし

## 説明

Sets the before-paragraph spacing for text; that is, the number of pixels to move down from the previous paragraph before starting the new paragraph. For vertical text mode, this function defines the vertical distance between paragraphs. If you apply dom.setTextParaSpacingAfter() in one paragraph, and dom.setTextParaSpacingBefore() in the second paragraph, the space between the two paragraphs would be the sum of both spacing arguments.

段落の間隔を設定します。新しい段落の開始前にピクセル数を入れ開始位置を下にずらします。縦書きの場合、段落間の垂直方向を定義します。1つ目の段落にdom.setTextParaSpacingAfter()を適用し、2つ目の段落にdom.setTextParaSpacingBefore()を適用した場合、2つの段落の間は両方の間隔を合算したものになります。
