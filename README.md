# News_Portal



## Authors
- [Abdallah Habib](https://github.com/Habib001-coder)


###  marking Schema
### SET MODE PostgreSQL;
* CREATE DATABASE newsapi;
 

*  \c newsapi

* CREATE TABLE  employees (
 id serial PRIMARY KEY auto_increment,
name VARCHAR,
position VARCHAR,
role VARCHAR,
address VARCHAR
);


* CREATE TABLE  news (
 id serial PRIMARY KEY auto_increment,
 title VARCHAR,
 content VARCHAR,
 depaertmentid INT
);

* CREATE TABLE  departments (
 id serial PRIMARY KEY auto_increment,
 department VARCHAR,
 description VARCHAR,
 number_employees INT
);
* CREATE DATABASE newsapi_test WITH TEMPLATE newsapi;





## Technologies Used
* Java
* Heroku
* postman

## Discription
This is a News API where one can add news, departments and even employers.


## Support and contact details
If you come across any problems you can reach me at: abdallah.abdul@student.moringaschool.com

### License
*This project is licensed under the terms of the MIT license.*
              Copyright (c) 2021 **Abdallah Habib Abdul**