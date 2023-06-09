## ブランチを切る

自分で作成した issue に取り組むために、ブランチを切りましょう。
ブランチをどのように切り、どのように命名し、どのようにマージするかという決まりをブランチ戦略と言います。ブランチ戦略にはさまざまなものがあります。今回は、簡単に擬似 issue 駆動開発型のブランチ戦略を取ります。

### ブランチを生成し、チェックアウトする

ブランチを切る方法は二種類あります。

##### branch コマンドを使用する

1. ブランチを作成する
   では。今回は`feat/#1`というブランチを作成してみましょう。今回の擬似 issue 駆動開発では`feat/<issueのID>`という形でブランチを切っていきます。

   ```
   git branch feat/#1
   ```

   > **Note**
   > ブランチ名には、`/`を最大一つまでしか含めないことに注意してください。
   > 例えば、` main``feat/main `等は許容されますが、` feat/main/1``feat/main/main `等は許容されません。

2. ブランチをチェックアウトする
   作成したブランチにチェックアウトします。

   ```
   git checkout feat/#1
   ```

   これによって、`feat/#1`というブランチ上で作業をすることができます。
