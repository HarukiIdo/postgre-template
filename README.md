# PostgreSQL docekr-compose Template
dockerを使ってローカルでPostgreSQLを使うためのサンプルです 

## 基本的なコマンド
### ターミナルを起動
デフォルトのデータベースに接続
`psql -d postgres`

データベースを指定して接続
`psql -d データベース名`

データベースとユーザを指定して接続
`psql -d データベース名 -U ユーザ名`

### DB
データベース一覧の表示
`\l`

データベースの選択
`\c データベース名`

### テーブル
テーブル一覧の表示
`\dt;`

テーブル構造の表示
`\d テーブル名;`

## 参考資料
[PostgreSQLの基本的なコマンド](https://qiita.com/H-A-L/items/fe8cb0e0ee0041ff3ceb)
