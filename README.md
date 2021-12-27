# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- ソースコードなどを記録して管理しておく場所のことをリポジトリというのですが、
サーバー上にあるリポジトリのことをリモートリポジトリといい、
個人のPC上にあるリポジトリのことをローカルリポジトリといいます。


## プッシュとマージの違いは何でしょうか？
- プッシュはローカルの変更内容をリモートに反映させるもので、
マージはあるブランチに変更内容を取り込んで反映させるものです。


## コミットとプッシュの違い
- コミットはステージングされた変更履歴をローカルに保存するもので、
プッシュはローカルで変更した内容をリモートに反映させるためのものです。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- どんな変更内容なのか、後で見返してもすぐに分かるような内容を書くのが適切です。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- プルリクエストでのマージは、マージがリモートでされていて
ローカルの方は最新の状態ではないので、変更された内容をプルする必要があります。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- コンフリクトが起こってしまったファイルの対象の箇所を正しい処理の形に修正し、
その変更が完了したらその内容をコミットします。