# Git Lesson
## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
* リモートリポジトリは複数人で共有するためのリポジトリのこと。
※代表的なものとしてGit Hubがある。
* ローカルリポジトリはユーザ一人ひとりが利用するために、自分のPC上に配置するリポジトリです。
## プッシュとマージの違いは何でしょうか？
* プッシュは、コミットをローカルリポジトリからリモートリポジトリに送る操作のことで、
* マージは別のブランチの作業内容(変更履歴)をマスターブランチに取り込むことのこと。
## コミットとプッシュの違い
* コミットはローカルリポジトリに変更を反映することができ、
* プッシュはリモートリポジトリに変更を反映することができる。
## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
* その履歴がどんな編集を行なったのかが、明確に分かるように書く必要がある。
## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
* ローカルでマージするフローの場合、
コードレビューをする前にmasterに反映されてしまうため、
コードにバグがあっても気づかない可能性がある。
* プルリクエストでマージするフローの場合は、
コードレビューをしてからマージするという手順を踏むため、
事前にバグを発見する事ができ、アップ後の重大なミスを予防することができる。
## コンフリクトを起こしてしまった場合、どう対処すべきですか？
* 以下の3通りの方法で変更を取り込む必要があります。
  1.先にマージされた変更内容を取り込む
  2.後にマージしようとしている変更内容を取り込む
  3.どちらの変更内容も取り込む
    ※③の場合は、エディタを使って両方の変更内容を取り込んだ処理で上書きする必要がある    。