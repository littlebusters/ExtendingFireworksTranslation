# dom.copyToHotspot()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS3827BD64-A0ED-40f4-AFE6-47326F82D391.html)

## バージョン

3

## 書式

```
dom.copyToHotspot(hotspotType, {whatIfMultipleSelected}, {makeRectangular})
```

## 引数

### hotspotType:

Acceptable values are "hotspot" and "slice".

許容値は```hotspot```と```slice```です。

### whatIfMultipleSelected:

An optional string that specifies how to create hotspots if multiple items are selected. Acceptable values for whatIfMultipleSelected are "single" (creates a single hotspot that has the same bounding rectangle as the selection), "multiple" (creates one hotspot for each item), and "ask user" (displays a dialog box to let the user decide). If whatIfMultipleSelected is omitted or null, "ask user" is assumed.

複数のオブジェクトが選択されている場合、ホットスポットを作成方法を指定するオプションのString型。whatIfMultipleSelectedの許容値は、```single```（選択範囲と同じ大きさの単一ホットスポットを作成） / ```multiple```（オブジェクトごとにホットスポットを作成） / ```ask user```（ダイヤログを表示し、ユーザーが決定）です。whatIfMultipleSelectedが省略または NULL のば場合は、```ask user```となります。

### makeRectangular:

An optional Boolean value that determines if the slice for the hotspot will be a rectangle or polygon. If true (the default), Fireworks creates a rectangular slice; otherwise, the slice is a polygon if the shape being copied to the slice is a polygon.

ホットスポット用のスライスを矩形または多角形にするかを決定するオプションのBoolean値。```true```（デフォルト値）の場合、Fireworksは矩形スライスを作成し、そうでないまたはコピーされた形状が多角形であれば、多角形スライスとなります。

## 戻り値

なし

## 説明

Creates one or more hotspots from the selection.

選択範囲から、1つまたはそれ以上のホットスポットを作成します。

## サンプル

The following command adds a hotspot to the selected item. If more than one item is selected, Fireworks creates one hotspot for each item.

次のコマンドを実行すると、選択されたオブジェクトにホットスポットを追加します。選択されたオブジェクトを2つ以上の場合、Fireworksは各オブジェクトにホットスポットを作成します。

```
fw.getDocumentDOM().copyToHotspot("hotspot", "multiple");
```