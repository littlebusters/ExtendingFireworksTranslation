# dom.shareLayerToPages()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7884.html)

## バージョン

CS3

## 書式

dom.shareLayerToPages(layerNum, addToPages, deleteFromPages)

## 引数

### layerNum:

A long value that indicates the layer number for the layer that is to be shared across pages. 

ページを超えて共有するレイヤーのレイヤー番号を示すLong型。

### addToPages:

A comma-separated string value that specifies the names of all pages that are adding the specified layer. 

指定されたレイヤーを追加するすべてのページを指定する、カンマで区切られたString型。

### deleteFromPages:

A comma-separated string value that specifies the names of all pages that are removing the specified layer. 

指定されたレイヤーを削除するすべてのページを指定する、カンマで区切られたString型。

## 戻り値

なし

## 説明

Shares or removes a specified foreground layer for specified pages. 

指定したページの指定したレイヤーを共有または非共有にします。
