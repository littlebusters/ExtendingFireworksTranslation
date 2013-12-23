# dom.moveSelectionToLayer()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7c72.html)

## バージョン

3、4でアップデート

## 書式

dom.moveSelectionToLayer(layerIndex, bMakeCopy, {whatIfMultipleSelected}, {elementIndex})

## 引数

### layerIndex:

An integer value that specifies the layer to which the selection should be moved or copied, starting with 0 (although, to specify the current layer, pass –1 here).

選択範囲の移動またはコピー先のレイヤーを指定する、0から始まるInteger型（現在のレイヤーを指定するには、-1を渡します）。

### bMakeCopy:

Boolean. If true, the selection is copied instead of moved.

Boolean型。```true```の場合、選択範囲をコピーせず移動します。

### whatIfMultipleSelected:

An optional string that is used only if the destination is a web layer and bMakeCopy is true. It specifies how to create hotspots if multiple items are selected. Acceptable values are "single" (creates a single hotspot that has the same bounding rectangle as the selection), "multiple" (creates one hotspot for each item), and "ask user" (displays a dialog box to let the user decide). If whatIfMultipleSelected is omitted or null, "ask user" is assumed. 

WebレイヤーかつbMaskCopyが```true```の場合のみ使用できる、オプションのString型。複数のオブジェクトを選択した場合、
ホットスポットの作成方法を指定します。許容される値は、```"singe"```（選択範囲を囲う1つの矩形ホットスポット） / ```"multiple"```（各オブジェクトごとにホットスポットを作成） / ```"ask user"```（ダイアログを表示しユーザーが決定）です。whatIfMultipleSelectedが省略されるまたはnullの場合、```"ask user"```となります。

### elementIndex:

A zero-based index, added in Fireworks 4, that specifies the element before which the moved or copied selection should be inserted. If elementIndex is omitted, the selection is placed at the top of the layer (before any other elements). Otherwise, it is an index within the existing elements in the layer, where 0 is the topmost, and (n-1) is the last element (for a layer with n elements). The maximum value is the number of elements previously in the layer—meaning that the elements are moved to the bottom of the specified layer.

Fireworks 4で追加された、移動またはコピーした選択範囲を挿入する要素の前を指定する、0から始まるインデックス。elementIndexが省略された場合、選択範囲はレイヤーのトップに配置されます（他の要素の前）。それ以外の場合、レイヤー内にある要素でのインデックスとなり、0が最上位、n-1が最後の要素（n個の要素を有するレイヤー）となります。最大値はレイヤー内の既存の要素数で、要素が指定されたレイヤーの底部に移動することを意味します。

## 戻り値

なし

## 説明

Moves or copies the selection to the specified layer.

選択範囲を指定したレイヤーに移動またはコピーします。