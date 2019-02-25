# study-docker-mysql
# 概要
mysql勉強用にdockerで環境を作る

## Goal
- `docker-compose up -d`でmysql, mysqladminが実行できる環境が構築されるようにする
  - docker-compose.ymlを書く
    - envは別ファイルに書く
- コンテナを削除してもデータが消えないように永続化する
  - data volumeを使用する
- 永続化したデータのbackup・restoreができるようにする
- MySQLWorkbenchが接続できるようにする
