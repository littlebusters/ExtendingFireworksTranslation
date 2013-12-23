# dom.duplicateFrame()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e0d.html)

## バージョン

3

## 書式

```
dom.duplicateFrame(frameIndex, howMany, where, bDupeSelectionOnly)
```

## 引数

### frameIndex:

An integer value that specifies the frame to duplicate, starting with 0 (although, to specify the current frame, pass –1 here).

0から始まる、複製するフレームを指定するInteger型。（現在のフレームを指定する場合は、-1を渡します）

### howMany:

An integer that specifies how many copies of the frame to make.

複製するフレーム数を指定するInteger型。

### where:

Acceptable values are "beginning", "before current", "after current", and "end". 

許容値は、```beginning```（一番上に挿入） / ```before current```（現在のステートの前に挿入） / ```after current```（現在のステートの後に挿入） / ```end```(一番下に挿入)です。

### bDupeSelectionOnly:

If bDupeSelectionOnly is true, only items in the specified frame that are selected are duplicated to the new frame.

bDupeSelectionOnlyが```true```の場合、指定されたフレームで選択されているオブジェクトを新しいフレームとして複製します。

## 戻り値

なし

## 説明

Duplicates a frame.

フレームを複製します。

## サンプル

The following command makes one copy of the current frame and places the new frame after the current frame:

次のコマンドを実行すると、現在のフレームを1つ複製し、現在のフレームの後に新しいフレームを配置します。

```
fw.getDocumentDOM().duplicateFrame(-1, 1, "after current", false);
```