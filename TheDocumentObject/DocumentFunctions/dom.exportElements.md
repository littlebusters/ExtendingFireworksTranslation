# dom.exportElements()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS0DC9B0EB-F673-49fe-A185-385E6359C973.html)

## バージョン

10

## 書式

```
dom.exportElements(elements, imagesUrl, name)
```

## 引数

### elements:

An array that contains the objects to be exported.

書き出しするオブジェクトが含まれる配列。

### imagesUrl:

Folder name to which the image is exported. Specified as file:///.

画像を書き出しするフォルダ名。```file:///```（ファイルパス）で指定します。

### name:

Name of the image.

画像の名前。

## 戻り値

なし

## 説明

Exports an array of elements on the canvas to a 32-bit PNG image, based on the image export settings.

画像書き出し設定に基づいて、カンバス上のオブジェクトを多数32bitPNG画像で書き出します。