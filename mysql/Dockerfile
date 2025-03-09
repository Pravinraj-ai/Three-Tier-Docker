FROM mysql:8

ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=user_data
ENV MYSQL_USER=admin
ENV MYSQL_PASSWORD=admin123

COPY db_init.sql /docker-entrypoint-initdb.d/
