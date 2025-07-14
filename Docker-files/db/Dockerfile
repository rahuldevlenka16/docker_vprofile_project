FROM mysql:8.0.33

#must be same as the pass and db in the application.properties
ENV MYSQL_ROOT_PASSWORD="vprodbpass" 
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql