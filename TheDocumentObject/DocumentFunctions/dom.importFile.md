# dom.importFile()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94988d-7f88.html)

## バージョン

3

## 書式

dom.importFile(fileURL, boundingRectangle, bMaintainAspectRatio)

## 引数

### fileURL:

The filename of the file to be imported, which is expressed as a file://URL.

file://URLのように表される、読み込むファイルのファイル名。

### boundingRectangle:

A rectangle that specifies the size to make the imported file (see Rectangle data type). If boundingRectangle is specified with left == right and top == bottom, the file is brought in unscaled with its top-left corner at the specified location, and the third argument is ignored. 

読み込むファイルのサイズを指定するRectangle型（Rectangle型を参照）。boundingRectangleが、left == right・top == bottomと指定された場合、ファイルはスケールされず左上コーナーの位置へ移動され、3番目の引数は無視されます。

### bMaintainAspectRatio:

If bMaintainAspectRatio is true, the file is scaled to the largest size that fits within boundingRectangle while retaining the file’s current aspect ratio. (This is a handy option for creating thumbnails.) If it is false, the file is scaled to fill boundingRectangle.

bMaintainAspectRatioが```true```の場合、ファイルはがboundingRectangle内に収まる最大のサイズに縦横比を保持したままスケールされます（これはサムネールを作るのに便利なオプションです）。```false```の場合、ファイルはboundingRectangleを埋めるようにスケールされます。

## 戻り値

なし

## 説明

Imports the specified file at the specified location.

指定された位置に、指定されたファイルを読み込みます。

## サンプル

The following command imports the specified file and maintains its aspect ratio:

次のコマンドを実行すると、縦横比を維持したまま指定したファイルを読み込みます。

```
fw.getDocumentDOM().importFile("file:///C|/images/foo.psd", {left:25, top:50, right:100, bottom:250}, true);
```