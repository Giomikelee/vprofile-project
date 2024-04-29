FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Kicha"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="vprodbpass"

ADD  db_backup.sql docker-entrypoint-initdb.d/db_backup.sql