# dom.moveFillVectorHandleBy()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7cb1.html)

## バージョン

3

## 書式

dom.moveFillVectorHandleBy(delta, whichHandle, bConstrain, bMoveJustOne)

## 引数

### delta:

A point that specifies the x,y coordinate values by which the handle is moved (see Point data type). For example, passing ({x:1,y:2}) specifies a location that is right by 1 pixel and down by 2 pixels.

移動させるハンドルのX/Y座標を指定するPoint型（Point型を参照）。例えば、```{ x: 1, y: 2 }```を渡すと、右に1ピクセル・下に2ピクセルの場所を指します。

### whichHandle:

Specifies which handle to move and can be one of the following values: "start", "end1", "end2", "rotate1", or "rotate2". (Some fills ignore "end2".) Use "rotate1" or "rotate2" to rotate the end1 or end2 point around the start point.

次のいずれかの値を移動させるハンドルに指定。```"start"``` / ```"end1"``` / ```"end2"``` / ```"rotate1"``` / ```"rotate2"```。（塗りは```end2```を無視します。）開始点を中心に、end1またはedn2を回転させるには```"rotate1"``` / ```"rotate2"```を使います。

### bConstrain:

Boolean. If true, movement is constrained to 45º increments.

Boolean型。```true```の場合、動作を45°に制限します。

### bMoveJustOne:

Boolean. If true, only the specified handle moves. If false, other handles might move in sync when the specified handle is moved.

Boolean型。```true```の場合、指定されたハンドルのみ移動します。```false```の場合、指定されたハンドルと同期して他のハンドルも移動します。

## 戻り値

なし

## 説明

If the selection has a fill that uses a fill vector (for example, a gradient fill), this function adjusts the handles of the fill vector. If the selection does not, this function has no effect.

選択範囲の塗りが、塗のベクトル（例えばグラデーションの塗り）を持っている場合、この関数は塗りのベクトルハンドルをを調整します。選択していない場合、この関数は効果がありません。