# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
*リモートリポジトリとは専用のサーバに配置して複数人で共有するためのリポジトリです。
*ローカルリポジトリとは開発者一人一人が利用するために、自分のPC上に配置するリポジトリです。


## プッシュとマージの違いは何でしょうか？
*プッシュとはローカルからリモートへ編集内容をアップすること。
*マージとは別のブランチの作業内容をブランチに取り込むこと。
*違いは作業内容の反映先がプッシュの場合「ローカル→リモート」マージの場合「別ブランチ→ブランチ」となることです。


## コミットとプッシュの違い
*コミットとはファイルやディレクトリの追加・変更を、リポジトリに記録すること。
*プッシュとはローカルからリモートへ編集内容をアップすること。
*違いはコミットは変更内容を記録すること、プッシュは「ローカル→リモート」へ変更内容をアップするところです。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
*基本的に他人が読むものなため、作業者が何故そこのコードを変更したのか理由が分かる様に簡潔に書くことが最適です。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
*ローカルでマージするフローの場合、コードをレビューする前にmasterに反映されるため、コードにバグがあっても気づかず本番環境にアップされ不具合などバグが発生します。
*プルリクエストでマージするフローの場合、コードレビュー後にマージをするため、事前にコードのバグを発見することができます。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
*自分以外の人が書いたコードを確認し、状況に応じて「先にマージされた変更内容を取り込む」「後にマージしようとしている変更内容を取り込む」「どちらの変更内容も取り込む」のどれかで取り込みを行う。
