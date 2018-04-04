# Revolution Official Store

Made by ham999dy
© 2018 Revolution Team

## Introduction

![Language](https://img.shields.io/badge/Language-PHP-blue.svg)
![Language](https://img.shields.io/badge/Database-SQLServer-red.svg) ![Language](https://img.shields.io/badge/Database-MySQL-orange.svg)
Revox Project is a shop written by our team with PHP,SQLSRV,MySQL Also we used free bootstrap templates from google.

The shop come with Admin Portal (you can delete it) also it work from inside the game only , You need to install MySQL server (I will not go into details)
also you need to install PHP with SQLSRV Drivers .

## Intallation
First you need to excute this SQL Query in your SQLServer to make the shop smp
[shop_login.sql](https://github.com/ham999dy/Revox-Project/blob/master/shop_login.sql)

After setting the MySQL server you need to open the SQL folder that included with the Shop archive and excute the sql files inside the MySQL server using phpMyAdmin (you can download it [from here](https://www.phpmyadmin.net/downloads/)), Then You need to edit the Config.php and the Admin/Config.php, Put all your correct MySQL & SQLserver connection information.

- When you add a new item the item goes to the MySQL database.
- When the player buy a new item the item will go to the BILLING database.
- The point table is inside the Auth database.