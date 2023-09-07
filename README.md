# sql
create database BookDB;
use BookDB;
create table Book(
ID int primary key,
title varchar(28),
author varchar(20),
genre varchar(20),
pub_year int(4),
price int);
insert into Book values(1,"race of life","ravi","thirller",1929,150);
insert into Book values(2,"dangerous","naga","horrer",2004,200);
insert into Book values(3,"help","sai","comedy",2006,500);
insert into Book values(4,"work","seshu","scifi",2006,500);
insert into Book values(5,"people","vamsi","work",2016,500);
insert into Book values(6,"education","krishna","work",2016,500);
insert into Book values(7,"earn","rohit","life",2017,590);
insert into Book values(8,"dog love","hari","education",2018,580);
insert into Book values(9,"safe","hara","work",2019,550);
insert into Book values(10,"working","raju","work",2015,400);
select * from Book;
select * from Book where title="help";
update Book set price=600 where price=400;
select * from Book;
delete from Book where title="safe";
select * from Book;
