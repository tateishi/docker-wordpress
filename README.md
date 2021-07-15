# docker-wordpress

## .env ファイル

`.env` ファイルに下記のように環境変数を定義する


```
MYSQL_ROOT_PASSWORD={{ mysqlのアドミンパスワード }}
MYSQL_DATABASE=wordpress
MYSQL_USER=wordpress
MYSQL_PASSWORD={{ wordpressの接続用パスワード }}

WORDPRESS_DB_HOST=mysql:3306
WORDPRESS_DB_NAME=wordpress
WORDPRESS_DB_USER=wordpress
WORDPRESS_DB_PASSWORD={{ wordpressの接続用パスワード }}

PMA_ARBITRARY=1
PMA_HOST=mysql
PMA_USER=wordpress
PMA_PASSWORD={{ wordpressの接続用パスワード }}

```
