# getting base image 
FROM mysql:5.7.25
# setting some labels 
LABEL Project="vprofile"
LABEL Author="Mohamed Mohsen"
# setting environment variable 
ENV MYSQL_ROOT_PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"
# copy mysql file 
COPY db_backup.sql docker-entrypoint-initdb/db_backup.sql