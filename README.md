# docker-compose_wordpress
dockerによる開発環境_wordpress

# 前提条件
docker for Mac インストール済
docker-composeインストール出来るPC

# docker_image
apache2
php 7.4.12
wordpress:latest
mysql:5.7

# database接続方法
ルートディレクトリに「.env」ファイルを作成し以下をコピペする(DB名、ユーザー名、PASSは任意に書き換えてください。)
`WORDPRESS_DB_NAME=wordpress`
`WORDPRESS_DB_USER=wp_user`
`WORDPRESS_DB_PASSWORD=hogehoge`

`MYSQL_RANDOM_ROOT_PASSWORD=yes`
`MYSQL_DATABASE=wordpress`
`MYSQL_USER=wp_user`
`MYSQL_PASSWORD=hogehoge`

## 参考文献
[Workship MAGAZINE様](https://goworkship.com/magazine/wordpress-docker/)
