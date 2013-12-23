#  dom.clipPaste()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7ed4.html)

## バージョン

3 アップデートした4

## 書式

```
dom.clipPaste({whatIfResolutionDifferent}, {whatIfPastingIntoElementMask})
```

## 引数

### whatIfResolutionDifferent:

An optional string that specifies how resampling should be done if the resolution of the clipboard contents doesn’t match the resolution of the document. Acceptable values for whatIfResolutionDifferent are "resample", "do not resample", and "ask user" (displays a dialog box to let the user decide). If whatIfResolutionDifferent is omitted or null, "ask user" is assumed.

ドキュメントとクリップボードの内容の解像度が異なる場合の、サンプリング方法を指定するオプションのString型。許容値は"resample"、"do not resamle"、"ask user"（ユーザーが判断できるようにダイアログボックスが表示される）です。値が省略またNULLの場合は、"ask user"になります。

### whatIfPastingIntoElementMask:

An optional argument, added in Fireworks 4, that applies only if the user is editing an element mask, and that element mask is an empty image mask. In this case, the pasted elements replace the existing mask (because it is essentially a mask that doesn’t mask anything). If the image mask isn’t empty, the pasted elements are added to the existing mask, rather than replacing it. Acceptable values for whatIfPastingIntoElementMask are "image", "vector", and "ask user". If whatIfPastingIntoElementMask is omitted or null, "ask user" is assumed.

ユーザーが要素のマスクを編集している場合かつ要素のマスクが空のビットマップマスクの場合に適用される、Fireworks 4より追加されたオプションの引数。この場合、ペーストされた要素は、既存のマスクを置き換えます（そのマスクは何もマスクしていないからです）。
ビットマップマスクが空ではない場合、ペーストされた要素は既存のマスクを置き換えるのではなく追加されます。
許容される値は、"image"、"vector"、"ask user"です。値が省略またはNULLの場合は、"ask user"となります。

## 戻り値

なし

## 説明

Pastes the clipboard contents into the document.

ドキュメントにクリップボードの内容をペーストします。

## 例

The following command pastes the clipboard contents into the document. If there is a need for resampling, Fireworks asks the user to decide how to resample.

次のコマンドを実行すると、クリップボードの内容をペーストします。リサンプルのひつようがあれば、Fireworksはリサンプルの方法をユーザーに尋ねます。

```
fw.getDocumentDOM().clipPaste();
```