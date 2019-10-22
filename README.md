# ISOI TECH-IT-OUT Registration Portal
Run index.html on XAMPP server

Saves DATABASE on .csv file.

Do not run csv file and .html simultaneously. 


## Docker-Compose support

- PHP 7.2 on Apache Server
- MySQL

Server on localhost:8000

```
docker-compose up --build
docker-compose up --build
docker-compose exec db bash
mysql -u root -p
Enter password: root
```

Then enter the following commands:
```
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY 'root';
```

