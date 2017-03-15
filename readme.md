This is a small example for beginers to start with jdbc.
I have used here eclipse ide to compile the files.

First you need to set up mySQL.

To do that follow these simple steps.
Go to the terminal and type in:
$ mysql -u root -p
//then provide the password
mysql>create database EMP;
mysql>use EMP;
mysql>create table Employees
 -> (
    -> id int not null,
    -> age int not null,
    -> first varchar (255),
    -> last varchar (255)
    -> );
mysql>INSERT INTO Employees VALUES (100, 18, 'Zara', 'Ali');  
mysql>INSERT INTO Employees VALUES (101, 25, 'Mahnaz', 'Fatma');
mysql>INSERT INTO Employees VALUES (102, 30, 'Zaid', 'Khan');

