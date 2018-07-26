## 平成進捗Master タスク管理アプリ「TasCal」

## エレベーターピッチ
「予定を追加して良いか分からない」を解決する
忙しい学生向けの
残り時間ベースで考えられる
タスク管理アプリ「TasCal」です。
これは、タスクに割ける時間の可視化ができ、
既存のタスク管理アプリやカレンダーアプリと異なり
即座にタスクに割くことができる時間を計算できる機能が備わっています。

## URL
* https://enpit-tascal.herokuapp.com/

## メンバー
https://github.com/Miwa-TKB<br>
https://github.com/inside-hakumai<br>
https://github.com/takashift<br>
https://github.com/MrSyTk<br>
https://github.com/ysumiya<br>

<!-- # TasCal (enPiT activity)

このリポジトリはenPiTで作成するアプリケーションのデータを含んでいます。

Herokuに自動デプロイを行っています。URLはこちら  
https://enpit-tascal.herokuapp.com/
  
**masterブランチに変更を加えると自動で差分が取り込まれます。コミットの際は注意してください**

## 必要要件
- ruby v2.4.4
- PostgreSQL v10.4

## 開発環境構築

### Ruby

各自rbenv等でバージョン2.4.4のrubyを導入してください。  
MacOS環境ならrbenvがHomebrewから取得できます。
```commandline
brew install rbenv
rbenv install 2.4.4
rbenv rehash
rbenv global 2.4.4
```

### bundlerのインストール
※rubyのバージョンを切り替えた場合は要実行(gemはrubyのバージョン毎に異なります)
```commandline
gem install bundler
```

### PostgreSQL
MacOS環境なら`brew install postgresql`で導入できます。  
開発を始める前にデータベースを編集する権限のあるPostgreSQLのユーザーを作成する必要があります。

```commandline
postgres -D /usr/local/var/postgres/
createuser -P -s <PostgreSQLのユーザー名>
Enter password for new role: <パスワード>
Enter it again: <パスワード>
```

ユーザーを作成したら、`.bashrc`や`.zshrc`等に以下を追記してください。
```
export TASCAL_DB_USER="<PostgreSQLのユーザー名>"
export TASCAL_DB_PASSWORD="<パスワード>"
```

ここまでやったら`bundle install`してリポジトリのディレクトリ下のGemfileに書かれているパッケージを入れましょう
```
bundle install
```

その後，リポジトリのディレクトリ下で以下のコマンドでデータベースを作成します。
```commandline
brew services start postgresql
bundle exec rake db:create
```
 -->