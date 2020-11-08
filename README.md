# docker-compose_wordpress
dockerによる開発環境_wordpress

# 前提条件(Mac)
docker for Mac
docker-composeインストール

# docker_image
apache2  
php 7.4.12  
wordpress:latest  
mysql:5.7

# database接続方法
ymlファイル内の以下を任意で書き換えてください。
```10行目：MYSQL_ROOT_PASSWORD: root用のパスワード```
```11・28行目：MYSQL_DATABASE: DB名```
```12・29行目：MYSQL_USER: DB接続用ユーザー名```
```13・30行目：MYSQL_PASSWORD: DB接続用パスワード```

## 参考文献
[Note](https://note.com/ignorant_kenji/n/nf0d961220338)
