---
sidebar_position: 1
---
 
# Introduction

## General
- When creating a new databases make sure to use MariaDB and set the collation to utf8mb4.

## Commands
To dump a database on the command line to a file,
```mysql
mysqldump -h <hostname/IP> -u <username> -p  <database> --add_drop_table -e > <YYYYMMDD-database>.sql
```