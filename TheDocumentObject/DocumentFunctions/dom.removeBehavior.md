# dom.removeBehavior()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c12.html)

## バージョン

3

## 書式

dom.removeBehavior({event}, {eventIndex})

## 引数
     
### event:

An optional argument specifying the event that triggers the behavior. This argument is ignored by Fireworks.

オプションの引数で、ビヘイビアのトリガーとなるイベントを指定。この引数はFireworksでは無視されます。

### eventIndex:

An integer value that specifies the location of the behavior to be removed, starting with 0 (although, to specify the end location, pass –1 here). This argument is optional.

If you omit both optional arguments this function removes all events from selected hotspots and slices.

ビヘイビアを削除する位置を指定する0から始まるInteger型（最後の位置を指定するには、-1を渡します）。この引数はオプションです。

どちらの引数も省略した場合、この関数は選択されたスライスとホットスポットから、すべてのイベントを削除します。

## 戻り値

なし

## 説明

Removes one or all behavior events from the selected hotspots and slices.

選択されたスライスとホットスポットから、1つ以上のイベントを削除します。

## 参照

dom.addBehavior()
