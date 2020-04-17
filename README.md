# dininghall
This is a dininghall system for courseSYSC5709Y design by contract Task 4.
Demo1:
First: create database of dininghall
 
Second: create table of ingredient_list
 
Insert some ingredients into the table with the order above;

Third: running the program mainTest111.java using eclipse.


Demo2:
First: create database of jdbc
(In mysql 5.7 database terminal)
CREATE DATABASE jdbc;
USE jdbc;
CREATE TABLE menu1(
             dish_id VARCHAR(20) PRIMARY KEY AUTO_INCREMENT,
             dish_name VARCHAR(30),
             price DOUBLE,
             quantity int
);
INSERT INTO menu1
VALUES(‘1’,‘Fried Chicken’,5,7), 
(‘2’,’ Boiled Fish in Hot Sauce’,10,8), 
(‘3’,’ Yu Shiang Pork’,12,10), 
(‘4’,’ Pork with Green Peppers’,6,12), 
(‘5’,’ Cumin Beef’,15,80), 
(‘6’,’ Kung Po Chicken’,12,0); 
 
Second: run “mainAPP.jave” in eclipse
 

