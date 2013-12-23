# dom.pathInset()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c5a.html)

## バージョン

3

## 書式

dom.pathInset(width, miter, join)

## 引数
     
### width:

A floating-point value that specifies the new width of the selected paths, in pixels. 

選択したパスの新しい幅を指定するピクセル単位のFloat型。

### miter:

A floating-point value that specifies the new miter angle of the selected paths, in pixels. This argument is ignored if the value of join is not "miter".

選択したパスの新しいマイター角度（角の比率）を指定するピクセル単位のFloat型。joinの値が```"miter"```ではない場合、この引数は無視されます。

### join:

Acceptable values are "bevel", "round", and "miter".

角の形状。許容される値は、```"bevel"``` / ```"round"``` / ```"miter"```。

## 戻り値

なし

## 説明

Performs an inset operation on the selected paths.

選択したパスに「パスの差し込み」操作を実行します。