FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD="vpropass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
