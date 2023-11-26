# ソフトウェア開発PBL内で重要な命名規則

## クラス図・シーケンス図の場合の命名規則
|識別子|規則|
|:--|:--|
|全体|・日本語は使わない<br>・省略を使わない|
|クラス名|アッパーキャメルケース|
|メソッド名|・ローワーキャメルケース<br>・必ず動詞から始める|
|変数名|・ローワーキャメルケース<br>・Boolean<br>is, has, 3単現動詞から始める<br>・date<br>????edOn・datetime<br>????edAt<br>※????は動詞|

## データベース図の場合の命名規則
|識別子|規則|
|:--|:--|
|全体|・大文字を使わない<br>・日本語は使わない<br>・省略を使わない|
|データベース名|・複数形<br>・スネークケース|
|テーブル名|・複数形<br>・スネークケース<br>・n:nのテーブルも複数形同士を繋ぐ|
|カラム名|・単数<br>・スネークケース|
