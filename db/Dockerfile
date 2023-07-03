FROM mysql:5.7

ENV MYSQL_ROOT_PASSWORD root

COPY ./mysql.cnf /etc/mysql/conf.d/mysql.cnf

COPY ./frodo.sql /docker-entrypoint-initdb.d/

