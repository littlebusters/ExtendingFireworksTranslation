# dom.clipPasteInside()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7eb9.html)

## バージョン

3、Fireworks 4で廃止予定のため、dom.clipPasteAsMask()を使う。

## 書式

```
dom.clipPasteInside({whatIfResolutionDifferent})
```

## 引数

### whatIfResolutionDifferent:

An optional string that specifies how resampling should be done if the resolution of the clipboard contents doesn’t match the resolution of the document. Acceptable values for whatIfResolutionDifferent are "resample", "do not resample", and "ask user" (displays a dialog box to let the user decide). If whatIfResolutionDifferent is omitted or null, "ask user" is assumed.

クリップボードの内容とドキュメントの解像度が一致しない場合の、リサンプル方法を指定するオプションのString型。whatIfResolutionDifferentの許容値は"resample"、"do not resamle"、"ask user"（ユーザーが判断できるようにダイアログボックスが表示される）です。値が省略またNULLの場合は、"ask user"になります。

## 戻り値

なし

## 説明

Pastes the clipboard contents into the selection, and places the selected element into the element mask for the pasted elements. If the selected element already has a mask, this function groups the pasted elements with the selected element and applies the existing element mask to the group.

選択範囲にクリップボードの内容を貼り付け、貼り付けたオブジェクトのマスク内にオブジェクトを配置します。選択されたオブジェクトにマスクがある場合、この関数は選択されたオブジェクトへの貼り付けられ、グループの既存オブジェクトマスクが適用されます。

## サンプル

The following command pastes the clipboard contents inside the selected items. If the resolution of the clipboard contents doesn’t match the resolution of the document, Fireworks resamples the clipboard contents to match the document.

次のコマンドを実行すると、選択したオブジェクトの内部にクリップボードの内容を貼り付けます。クリップボードの内容とドキュメントの解像度が一致しない場合、Fireworksはドキュメントの解像度と一致するように、クリップボードのの内容をリサンプリングします。

```
fw.getDocumentDOM().clipPasteInside("resample");
```