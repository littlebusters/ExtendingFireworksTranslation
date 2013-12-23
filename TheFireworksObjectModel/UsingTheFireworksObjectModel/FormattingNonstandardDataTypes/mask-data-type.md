# Mask data type

The format for a mask is {maskBounds:rectangle, maskKind:string, maskEdgeMode:string, featherAmount:int, maskData:hex-string}.

マスクのフォーマットは、```"{maskBounds:rectangle, maskKind:string, maskEdgeMode:string, featherAmount:int, maskData:hex-string}"```です。

* maskBounds specifies the bounding rectangle of the mask area.
* Acceptable values for maskKind are "rectangle", "oval", "zlib compressed", "rle compressed", or "uncompressed".
* If the value of maskKind is "rectangle" or "oval", the maskData string is ignored, and a mask of the right shape is constructed that fills maskBounds and that has the edge specified by maskEdgeMode and featherAmount.
* If the value of maskKind is “zlib compressed“, “rle compressed", or “uncompressed", the maskData string is presumed to contain 8bit mask data in hexadecimal format that precisely matches the maskBounds to define the mask.

* maskBoundsは、マスクエリアの境界の矩形を指定します。
* maskKindで許容できる値は、```"rectangle"```（矩形） / ```"oval"```（楕円） / ```"zlib compressed"```（zlib圧縮） / ```"rle compressed"```（rle圧縮） / ```"uncompressed"```（無圧縮）です。
* maskKindの値が```"rectangle"```または```"oval"```の場合、maskDataは無視され、適切なマスクの形状として、maskEdgeModeとfeatherAmoutで指定されたエッジを持つmaskBoundsの塗りで構成されます。
* maskKindの値は、```“zlib compressed“``` / ```“rle compressed"``` / ```“uncompressed"```の場合、maskDataの文字列は、マスクを定義するmaskBoundsと一致する16進数の8ビットマスクのデータを含むものと推測されます。