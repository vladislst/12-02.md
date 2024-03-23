# Домашнее задание к занятию "`Работа с данными (DDL/DML)`" - `Степанов Владислав`

### Задание 1

CREATE USER 'sys_temp'@'localhost' IDENTIFIED BY '123456';  
SELECT user,host FROM user;
![Image alt](https://github.com/vladislst/12-02.md/raw/main/img/1.jpg)  
GRANT ALL PRIVILEGES ON *.* TO 'sys_temp'@'localhost';  
SHOW GRANTS FOR 'sys_temp'@'localhost'\G;  
![Image alt](https://github.com/vladislst/12-02.md/raw/main/img/2.jpg)
exit  
mysql -u sys_temp -p  
exit  
mysql -u sys_temp -p < sakila-schema.sql  
mysql -u sys_temp -p < sakila-data.sql  
show tables from sakila  
![Image alt](https://github.com/vladislst/12-02.md/raw/main/img/3.jpg)  

### Задание 2  

[sakila xls](https://github.com/vladislst/12-02.md/raw/main/sakila.xlsx)

