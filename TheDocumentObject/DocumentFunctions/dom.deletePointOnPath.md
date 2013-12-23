# dom.deletePointOnPath()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7e4d.html)

## バージョン

4

## 書式

```
dom.deletePointOnPath(contourIndex, pointIndex)
```

## 引数

### contourIndex:

An integer value that specifies the contour that contains the point to be deleted, starting with 0 (although, to specify the current contour, pass –1 here).

0から始まる、削除するセグメントを含むアンカーポイントを指定するInteger型。（現在のセグメントを削除するには、-1を渡します）

### pointIndex:

An integer value that specifies the point to be deleted, starting with 0 (although, to specify the current point, pass –1 here).

0から始める、削除するアンカーポイントを指定するInteger型。（現在のアンカーポイントを削除するには、-1を渡します）

## 戻り値

なし

## 説明

Deletes the specified point on the currently selected path. If the point is the only one on its contour, the entire contour is deleted. If the point is the only one in the path, the entire path is deleted. The specified point does not need to be selected.

選択された現在のパス上で、指定されたアンカーポイントを削除します。アンカーポイントがセグメント上に1つしかない場合、セグメントが削除されます。アンカーポイントがパス上に1つしかない場合、パス全体が削除されます。指定されたポイントを選択しておく必要はありません。

## サンプル

The following command deletes the currently selected point:

次のコマンドを実行すると、選択されているアンカーポイントが削除されます。

```
fw.getDocumentDOM().deletePointOnPath(-1, -1);
```