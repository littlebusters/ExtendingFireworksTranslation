# dom.duplicateSelectionToFrameRange()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7df7.html)

## バージョン

3

## 書式

```
dom.duplicateSelectionToFrameRange(frameIndexFirst, frameIndexLast)
```

## 引数

### frameIndexFirst / frameIndexLast:

Integer values that specify the range of frames (inclusive) to which the items should be copied, starting with 0 (although, to specify the current frame, pass –1 here).

- If both arguments are the same, duplicates are placed only on that frame.
- If the range includes the current frame, duplicates are not placed on that frame.

0から始まる、複製するフレームの範囲（両端を含む）を指定するInteger型。（現在のフレームを指定するには-1を渡します）

- どちらの引数も同じ場合、そのフレームにのみ複製されます。
- 現在のフレームを含む範囲の場合、複製したものはフレームに配置されません。

## 戻り値

なし

## 説明

Duplicates the selection to a range of frames of the document.

ドキュメントのフレームの範囲で選択範囲を複製します。