# Current Quality Gate Status

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=softcreative2580_actioncode&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=softcreative2580_actioncode)

## Base Tools

- JDK 11
- Maven 3
- MySQL 8

## Technologies

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

## Database

Here,we used Mysql DB
MSQL DB Installation Steps for Linux ubuntu 14.04:

- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :

- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
