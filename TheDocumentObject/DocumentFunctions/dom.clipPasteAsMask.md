# dom.clipPasteAsMask()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7fd7.html)

## バージョン

4

## 書式

```
dom.clipPasteAsMask(whatIfResolutionDifferent, masktype, maskReplaceOptions)
```

## 引数

### whatIfResolutionDifferent:

A string that specifies how resampling should be done if the resolution of the clipboard contents doesn’t match the resolution of the document. Acceptable values for whatIfResolutionDifferent are "resample", "do not resample", and "ask user" (displays a dialog box to let the user decide). If whatIfResolutionDifferent is omitted or null, "ask user" is assumed.

ドキュメントとクリップボードの内容の解像度が異なる場合の、サンプリング方法を指定するオプションのString型。許容値は"resample"、"do not resamle"、"ask user"（ユーザーが判断できるようにダイアログボックスが表示される）です。値が省略またNULLの場合は、"ask user"になります。

### masktype:

Specifies how to paste the mask. Acceptable values are “image“ (always paste as an image mask), “vector“ (always paste as a vector mask), and “ask“ (displays a dialog box to let the user decide). If the clipboard contains a single image, it is pasted as an image mask, even if you pass “vector“.

マスクを貼り付ける方法を指定します。許容値は、```image```（常にビットマップマスクとして貼り付け） / ```vector```（常にベクトルマスクとして貼り付け） / ```ask```（ユーザーが選択できるようにダイヤログを表示）です。クリップボードが単一の画像だった場合、引数を```vector```として渡しても、ビットマップマスクとして貼り付けられます。

マスクを貼り付ける方法を指定します。許容値は、 "イメージ"（常にイメージマスクとして貼り付け）、 "ベクトル"（常にベクトルマスクとして貼り付け）と、（ユーザーが判断できるように、ダイアログボックスを表示します） "お願い"です。クリップボードは、単一の画像が含まれている場合は、"ベクトル"を渡した場合でも、それは、ビットマップマスクとして貼り付けられます。

### maskReplaceOptions:

Acceptable values for maskReplaceOptions are “replace“ (if an element mask already exists, replace it with the pasted one), “add“ (if an element mask already exists, add the pasted mask to it), and “ask“ (displays a dialog box to let the user decide).

maskReplaceOptionsの許容値は、"置換"（エレメント·マスクがすでに存在する場合は、貼り付けられたものと交換）、（要素マスクがすでに存在する場合、それに貼り付けマスクを追加） "を追加します"、と（表示する、 "尋ねる"ですダイアログボックスは、ユーザーが）決めさせてください。

## 戻り値

なし

## 説明

Pastes the clipboard contents into the document as an element mask. Only one element can be selected when calling this function. If more than one element (or none) is selected when this function is called, Fireworks throws an exception. An exception is also thrown if there is nothing on the clipboard.
 
要素マスクとしてドキュメントにクリップボードの内容を貼り付けます。この関数を呼び出すときに、要素は1つだけ選択することができます。この関数が呼び出されたときに複数の要素（またはnone）が選択されている場合、Fireworksは例外をスローします。クリップボードに何も表示されない場合にも例外がスローされます。