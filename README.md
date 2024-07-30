# Nodejs with MySQL

# INDEPENDENT MYSQL DOCKER FOR DEVELOPMENT
- `docker run --name sqldb -d -p 3306:3306 -v mysqldata:/var/lib/mysql -e MYSQL_ROOT_PASSWORD='test' mysql:latest`


## HOW TO RUN THIS REPO

- `npm install`
  ### Dev
  - `npm run dev`

# SET UP MYSQL EXEC IN DOCKER
- `mysql -u root -ptest`
- `CREATE DATABASE ecom;`
- `use ecom;`

- CREATE TABLE products(
     id INT PRIMARY KEY AUTO_INCREMENT,
     title VARCHAR(32) NOT NULL,
     description VARCHAR(255) NOT NULL,
     price INT NOT NULL
 );

- `show tables;`
- `desc table_name;`
