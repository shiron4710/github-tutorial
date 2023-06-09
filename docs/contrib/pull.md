## プルについて

もしかしたら誰か、共同開発者が更新をしているかもしれません。それに CI/CD によってブランチに更新が入っている可能性もあります。そのため、新しい作業に入る前には Pull を行いましょう。

Pull を行うことにより、リモートリポジトリのブランチのコミットをローカルリポジトリのコミットに取り込むことができます。つまり、リモートリポジトリで誰かが変更したのを自分のパソコンに取り込む作業と言えるでしょう。

1. Pull を行う
   次のコマンドを実行することにより Pull を行えます。

   ```
   git pull
   ```

   ここで、コンフリクトが発生した等のメッセージが表示された場合は、先にこちらを参照してください。[コンフリクトを解決する](/docs/contrib2/conflict.md)
