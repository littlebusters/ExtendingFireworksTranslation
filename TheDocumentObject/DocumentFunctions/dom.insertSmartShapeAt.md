# dom.insertSmartShapeAt()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d0d.html)

## バージョン

MX 2004

## 書式

dom.insertSmartShapeAt(name, location, useToolBlendModeOpacity)

## 引数

### name:

A string specifying the name of the Auto Shape.

オートシェイプの名前を指定するString型。

### location:

The upper-left point of the Auto Shape.

オートシェイプの左上の座標。（Point型）

### useToolBlendModeOpacity:

Determines whether the new shape object should have the blend mode and opacity settings set for the Auto Shape Tools (set by the user in the Property inspector), or use standard values. The bUseToolBlendModeOpacity argument is a Boolean value: true if the shape will use the blend mode and opacity set for the Auto Shape Tools; false if the shape will use the standard values (alpha blend mode and 100% opacity).

新しいシェイプオブジェクトに、設定した不透明度と合成モードを適用するか（ユーザーがプロパティインスペクタで設定）、標準値を使用するかを決定します。bUseToolBlendModeOpacityはBoolean型の引数です。```true```ならば、シェイプはオートシェイプの不透明度とブレンドモードの設定が使われます。```false```ならば、シェイプは標準値が使われます。（アルファ合成モードと不透明度100%）

## 戻り値

なし

## 説明

Inserts an Auto Shape at the specified location. 

指定した場所にオートシェイプを挿入します。