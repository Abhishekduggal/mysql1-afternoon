# mysql1-afternoon
SQL 1 afternoon Project - Complete

/* create table Person (
  id integer primary key autoincrement,
  name varchar(1500),
  age int,
  height int,
  city varchar(100),
  favoritecolor varchar(100)
  ); */
  
/*   drop table person */
/*   insert into Person (name, age, height, city, favoritecolor)
  values 
    ('Jerry', 53, 110, 'NY', 'Blue'),
    ('Harry', 32, 160, 'Bronx', 'Red'),
    ('Ian', 53, 180, 'Dallas', 'White'),
    ('Joe', 53, 120, 'Texas', 'Black'),
    ('Jack', 53, 80, 'Vancouver', 'Yellow'); */
  
/*   select * from person; */

/* select * from person order by(height) desc; */

/* select * from person order by(height) asc; */

/* select * from person order by(age) desc; */

/* select * from person where age>20; */

/* select * from person where age=18; */

/* select * from person where age>20 and age<30; */

/* select * from person where age <> 53; */

/* select * from person where favoritecolor <> 'Red'; */

/* select * from person where favoritecolor <> 'Red' and favoritecolor <> 'Blue'; */

/* select * from person where favoritecolor <> 'Orange' or favoritecolor <> 'Green' */

/* select * from person where favoritecolor = 'Red' or favoritecolor = 'Blue' */

/* select * from person where favoritecolor in ('Blue') or favoritecolor in ('Red'); */



/* Table Artist */

/* select * from Artist; */

/*   insert into Artist (name)
  values 
    ('Ed Sheeran'),
    ('Atif Aslam'),
    ('Salim Marchant')
     */
    
/* select * from Artist;     */
/* 
select * from Artist order by Name desc limit 10 */

/* select * from Artist order by Name asc limit 5 */

/* select * from Artist where name like 'Black%'; */

/* select * from Artist where name like '%Black%'; */


/* Table Employee */

/* select * from Employee; */

/* select FirstName, LastName from Employee where City='Calgary'; */

/* select FirstName, LastName, max(Birthdate) from Employee; */

/* select FirstName, LastName, min(Birthdate) from Employee; */

/* select * from Employee; */
/* select * from Employee where ReportsTo = 2; */

/* select count(City) from Employee where City='Lethbridge'; */


/* Table Invoice */

/* select * from Invoice; */

/* select count(*) from Invoice where BillingCountry = 'USA'; */

/* select max(Total) from Invoice; */

/* select min(Total) from Invoice; */

/* select * from Invoice where Total > 5; */

/* select * from Invoice where Total < 5; */

/* select count(*) from Invoice where Total < 5; */

/* select * from Invoice where BillingState in ('CA','TX','AZ');  */

/* select avg(Total) from Invoice; */

/* select round(sum(Total),1) from Invoice; */

