# About

DDDを採用した。

ただし、表示系の処理はQueryServiceという名前のクラスを作成し、専用のDTOにデータを詰め込んで返すように実装する。

これでEntityは更新系、データの整合性に集中できる。

しかしクラス数が増えるし、データを取得するインフラ層のファイルも増えてしまう。