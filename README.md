# data-base-managment
create table empl
(
empid number(5),
name varchar(30),
dept varchar(10),
doj date,
dob date,
salary number(5)
);
insert into empl(empid,name,dept,doj,dob,salary)values(1,'lavi','mba','10-jan-2020','1-dec-1997',25000);
insert into empl(empid,name,dept,doj,dob,salary)values(2,'sourav','mca','3-dec-2019','3-feb-1998',30000);
insert into empl(empid,name,dept,doj,dob,salary)values(3,'abhishek','mba','7-march-2018','17-april-1996',23000);
select * from empl
