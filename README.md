# study-docker-mysql
# 概要
mysql勉強用にdockerで環境を作る

## Goal
- `docker-compose up -d`でmysql, phpmyadminが実行できる環境が構築されるようにする
  - docker-compose.ymlを書く
    - envは別ファイルに書く
- コンテナを削除してもデータが消えないように永続化する
  - data volumeを使用する
- 永続化したデータのbackup・restoreができるようにする
- MySQLWorkbenchが接続できるようにする
- コンテナを立ち上げたらDBにデータが用意されているようにする
  - どのデータが入っている状態にするかはこれから決める

## 参考にするサイト
mysql + phpmyadminの設定
https://morizyun.github.io/docker/docker-compose-mysql-phpmyadmin.html

MySQLWorkbench接続に関して
https://qiita.com/hihats/items/370a195209bf3bef2401

起動したらDBにデータが入っているようにする方法
https://kakakakakku.hatenablog.com/entry/2017/11/08/193031