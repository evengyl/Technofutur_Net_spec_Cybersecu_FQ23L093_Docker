FROM mysql:latest

EXPOSE 3306

ENV MYSQL_ROOT_PASSWORD="test1234"
ENV MYSQL_DATABASE="docker_sql"
ENV MYSQL_USER="evengyl"
ENV MYSQL_PASSWORD="test1234"

COPY ./init.sql /docker-entrypoint-initdb.d/