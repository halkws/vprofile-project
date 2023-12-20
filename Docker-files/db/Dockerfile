FROM mysql:8.0.33 
LABEL "Project"="Vprofile"
LABEL "Author"="Kostas"


ENV MYSQL_ROOT_PASSWORD="abc123"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql