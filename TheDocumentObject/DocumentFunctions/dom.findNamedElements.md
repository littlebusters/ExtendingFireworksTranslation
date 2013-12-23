# dom.findNamedElements()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7d89.html)

## バージョン

4

## 書式

```
dom.findNamedElements(name)
```

## 引数

### name:

A case-sensitive string that specifies the exact element name to find. To specify elements that have no name, pass null.

探し出すオブジェクト名を正確に指定する、大文字・小文字を区別されるString型。名前のないオブジェクトを指定するには、```null```を渡します。

## 戻り値

An array of elements that have the specified name, or null if no objects have the specified name.

指定された名前のオブジェクトの配列または指定された名前のオブジェクトがない場合はnullとなります。

## 説明

Looks for elements that have the specified name.

指定された名前のオブジェクトを探します。

## 参照

dom.setElementName()