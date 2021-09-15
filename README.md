# Befehle zum Einrichten

## In Console:
apt install nano
nano /etc/mysql/mysql.conf.d/mysqld.cnf

Strg+X / Y / Enter

mysql-ctl cli;

## In CLI:
CREATE USER 'peter'@'%' IDENTIFIED BY 'abcd1234#';
GRANT ALL PRIVILEGES ON *.* TO 'peter'@'%';

SELECT * FROM mysql.user;
quit;

## In Console:
mysql-ctl restart 

# Befehle zum Betrieb
mysql-ctl Start
