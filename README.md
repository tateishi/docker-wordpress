# docker-wordpress

## .env ファイル

`.env` ファイルに下記のように環境変数を定義する


```
MYSQL_ROOT_PASSWORD={{ mysqlのアドミンパスワード }}

WORDPRESS_DB_HOST=mysql:3306
WORDPRESS_DB_NAME=wordpress
WORDPRESS_DB_USER=wordpress
WORDPRESS_DB_PASSWORD={{ wordpressの接続用パスワード }}

```
