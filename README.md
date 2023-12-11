# ソフトウェア開発PBL内で重要な命名規則

ここでは, 一般的にソフトウェア開発で利用される命名規則について, まとめたものを記載する. <br>
これらの命名規則は, 以下のサイトから引用している. <br>
https://qiita.com/yimajo/items/a3fac0026c07ec538fc2
https://qiita.com/genzouw/items/35022fa96c120e67c637

## クラス図・シーケンス図の場合の命名規則
|識別子|規則|
|:--|:--|
|全体|・日本語は使わない<br>・省略を使わない|
|クラス名|アッパーキャメルケース|
|メソッド名|・ローワーキャメルケース<br>・必ず動詞から始める|
|フィールド名|・ローワーキャメルケース<br>・Boolean<br>is, has, 3単現動詞から始める<br>・date<br>????edOn<br>・datetime<br>????edAt<br>※????は動詞|

## データベース図の場合の命名規則
|識別子|規則|
|:--|:--|
|全体|・大文字を使わない<br>・日本語は使わない<br>・省略を使わない|
|データベース名|・複数形<br>・スネークケース|
|テーブル名|・複数形<br>・スネークケース<br>・n:nのテーブルも複数形同士を繋ぐ|
|カラム名|・単数<br>・スネークケース|
