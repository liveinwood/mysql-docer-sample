# MySQL構築用のDockefile

ディレクトリ直下に以下の内容で`.env`を置いておけばOK。

```
COMPOSE_PROJECT_NAME=プロジェクト名

MYSQL_ROOT_PASSWORD=rootユーザのパス
MYSQL_DATABASE=DB名
MYSQL_USER=DBユーザ名
MYSQL_PASSWORD=DBユーザのパス
MYSQL_PORT=ホスト側ポート番号

```

`COMPOSE_PROJECT_NAME`を指定することで、コンテナ名が重複しない。

参考:https://qiita.com/TAMIYAN/items/ed9ec892d91e5af962c6