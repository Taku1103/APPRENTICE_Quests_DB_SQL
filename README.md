# Nettvデータベース作成手順
1. MySQLにrootユーザー等のデータベース（以下DB）作成権限等をもつ高位のユーザーでアクセスし、任意の名前のDBを作成する（以下DB名を'nettv'とする）。
2. コマンド use nettv; でDBを指定。
3. [./Create_NetTV.sql](./Create_NetTV.sql) のファイル内にあるSQLを上から順に実行する。

# STEP3のSQL
[./Queries_NetTV.sql](./Queries_NetTV.sql) のファイル内にあるSQLを実行する。クエストの番号とコマンド上部にある番号が対応している。
## 補足
-3

本日を'2023-11-07'とする

-4

本日を'2023-11-07'とする
特定のチャンネル名'NKK'とする

-5

直近の一週間をそのSQL文を実行した日付（JST）の一週間以内とする

# ER図
![ER図](./NeoInternetTV.png)

# テーブル設計
