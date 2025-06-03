
# MySQL Cheat Sheet
## Datatypes
```sql
int / int(n)
char(n)
varchar(n)
float / decimal
date
text
```

## Show Databases and Tables

```sql
show databases;
show tables;
```

## Create Database and Table

```sql
create database param;
use param;

create table student (
	roll int,
	fname varchar(20),
	lname varchar(20),
	city varchar(20),
	phone_no varchar(10),
	math int,
	sci int,
	eng int
);
```

## Insert Data

```sql
insert into student values(1,'param','shah','goa','1234556789',50,35,10);
-- add other rows similarly
insert into student(roll) values(21);
```

## Select

```sql
select * from student;
select roll, fname, lname from student;
select fname as 'Name', roll as 'ROLL_ID' from student;
```

## Where Clause

```sql
select * from student where city='mumbai';
select * from student where math>=35;
select * from student where city='mumbai' or city='goa';
select * from student where math>=60 and eng>=50;
```

## Like

```sql
select * from student where fname like 'h%';
select * from student where fname like '____';
select * from student where fname like 'p___';
```

## Order By

```sql
select * from student order by city;
select * from student order by fname desc;
```

## Aggregate Functions

```sql
select min(math) from student where city='mumbai' or city='goa';
select * from student where math = (select max(math) from student);
select * from student where sci >= (select avg(sci) from student);
```

## Constraints

```sql
create table emp(
	id int primary key,
	name varchar(10) not null,
	pid int unique
);

create table demo(
	age int check (age >18),
	city varchar(20) default 'pune'
);
```

## Alter Table

```sql
alter table student add gender char(1);
alter table student modify gender varchar(4);
alter table student drop column gender;
alter table student change column gender Gender varchar(4);
alter table student rename to stud;
```

## Update

```sql
update stud set gender='Female' where roll=2;
update stud set gender='F' where roll in (5,7,11,14,9,16,17,20);
update stud set roll=roll+100;
```

## Copy Table

```sql
create table newtest as select * from emp;
```

## Transactions

```sql
start transaction;
set autocommit=off;
commit;
rollback;
```

## Triggers

```sql
delimiter $
create trigger mytri
after insert on demo
for each row
begin
	insert into demo_backup values(new.city);
end$
delimiter ;

delimiter $
create trigger class_update
before update on demo
for each row
begin
	update demo set city='goa' where age=24;
end$
delimiter ;
```

## Delete

```sql
delete from stud where roll=21;
delete from stud;
truncate table stud;
drop table student;
drop database param;
```

## Joins

```sql
select course.subject, stud.fname, course.cid
from course left join stud on course.roll=stud.roll;

select course.subject, stud.fname, course.cid
from course right join stud on course.roll=stud.roll;

select course.subject, stud.fname, course.cid
from course, stud where course.roll=stud.roll;
```

## Export to CSV

```sql
select fname, cid from course into 
outfile "C:\\ProgramData\\MySQL\\MySQL Server 8.1\\Uploads\\demo.csv"
fields terminated by ','
enclosed by '"'
lines terminated by '\n';
```

## Load Data from CSV

```sql
load data infile "C:\\ProgramData\\MySQL\\MySQL Server 8.1\\Uploads\\Book1.csv"
into table book
fields terminated by ','
enclosed by '"'
lines terminated by '\n'
ignore 1 rows;
```

---

## Additional Useful Commands

### Indexing for Performance

```sql
create index idx_city on student(city);
drop index idx_city on student;
```

### Group By and Having

```sql
select city, avg(math) from student group by city;
select city, avg(math) from student group by city having avg(math)>50;
```

### Union

```sql
select fname from student where math>=50
union
select fname from student where sci>=50;
```

### IFNULL and COALESCE

```sql
select fname, ifnull(phone_no, 'No Phone') from student;
select fname, coalesce(phone_no, 'No Phone') from student;
```

### Date/Time Functions

```sql
select now();
select curdate();
select curtime();
select year(curdate());
```

### Stored Procedure

```sql
delimiter //
create procedure show_students()
begin
	select * from student;
end//
delimiter ;

call show_students();
```

### Views

```sql
create view high_scores as
select fname, math from student where math>80;

select * from high_scores;
drop view high_scores;
```



