# dom.setGroupType()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-79f3.html)

## バージョン

3、引数は4で廃止予定

## 書式

dom.setGroupType({type})

## 引数

### type

An optional string that specifies how to group the items. Acceptable values are "normal", "mask to image", and "mask to path". If the argument is omitted, "normal" is assumed. (The "mask to image" and "mask to path" values are deprecated in Fireworks 4.)

オブジェクトのグループ化の方法を指定するオプションの文字列。許容値は```"normal"``` / ```"mask to image"``` / ```"mask to path"```。引数を省略した場合は、```"normal"```を指定指定したものとみなします。（```"mask to image"```と```"mask to path"```は、Fireworks4で廃止されました）

## 戻り値

なし

## 説明

Changes the group type of the currently selected groups.

現在選択しているグループのグループタイプを変更します。
