# dom.adjustExportToSize()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7f56.html)

## バージョン

3

## 書式

```
dom.AdjustExportToSize(sizeInBytes, bOkToIncreaseSize)
```

## 引数

### sizeInBytes:

書き出しサイズを指定するInteger型。

- ドキュメントにスライスがない場合、sizeInBytes以下になるよう、現在のフレームの書き出し設定を調整します。
- ドキュメントにスライスがある場合、sizeInBytes以上になるよう、画像ファイルサイズを調整します。

### bOkToIncreaseSize:
：書き出しファイルサイズがsizeInBytes未満の場合、：書き出しファイルサイズを増加させてもよいかを指定するBoolean型。

- bOkToIncreaseSizeが```true```で現在のファイルサイズがsizeInBytes未満の場合、書き出しファイルサイズを増やすことで品質が向上します。
- bOkToIncreaseSizeが```false```の場合、書き出しファイルサイズを増やすことなく可能な範囲で品質を向上させます。

## 説明

指定された書き出し設定を調整します。