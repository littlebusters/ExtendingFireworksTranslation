# dom.reorderFrame()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7be1.html)

## バージョン

3

## 書式

dom.reorderFrame(frameToMove, frameToPutItBefore, bMakeCopy)

## 引数
     
### frameToMove:

A zero-based index that specifies which frame to move or copy.

移動またはコピーするフレームを指定する0から始まるインデックス。

### frameToPutItBefore:

A zero-based index that specifies where to place the frame that is to be moved or copied. For example, if you pass 1 for frameToMove and 0 for frameToPutItBefore, the second frame is placed before the first frame.

移動またはコピーするフレームの配置を指定する0から始まるインデックス。例えば、frameToMoceに1を、frameToPutItBeforeに0を渡した場合、2番目のフレームは最初のフレームの前に配置します。

### bMakeCopy:

Boolean. If true, the specified frame is copied instead of moved.

Boolean型。```true```ならば、指定されたフレームはコピーせず移動します。

## 戻り値

なし

## 説明

Moves or copies the specified frame before another specified frame.

指定したフレームを別の指定されたフレームの前に移動またはコピーします。

## サンプル

The following command moves the third frame before the first frame:

次のコマンド実行すると1番目のフレームの前に3番目のフレームを移動します。

```
fw.getDocumentDOM().reorderFrame(2, 0, false);
```
