# dom.undo()

[Original Document](http://help.adobe.com/en_US/fireworks/cs/extend/WS5b3ccc516d4fbf351e63e3d1183c94856c-7864.html)

## バージョン

3

## 書式

dom.undo()

## 引数

なし

## 戻り値

なし

## 説明

Undoes the most recent step performed, as long as that step is actually able to be undone; meaning, if you use a command that contains multiple JavaScript instructions, then you can undo the command (all 10 JavaScript instructions) and not just one JavaScript instruction within that command. Most (but not all) JavaScript functions cause an action to be executed that cannot be undone. 

取り消しできるステップがある限り、直前のステップに戻します。複数のJavascriptが含まれているコマンドを使用する場合、（10のJavascriptが含まれる）コマンドに含まれる1つだけではなく全体のコマンドを取り消します。ほとんどのJavascript関数のアクションは、実行後、元に戻すことはできません。（コマンドに含まれる関数単位の話？）
