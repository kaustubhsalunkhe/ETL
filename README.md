# ETL

A Simple Project For creating A Database in postgreSQL and Doing the ETL Process on the database on postgreSQL.

# Reuired libraries 
import psycopg2
import pandas as pd
from sqlalchemy import create_engine

# 1. Create a Database in PostgreSQL by using the following commands 
create table customer_info (
id serial Primary key,
full_name Varchar(100),
age int
);

insert into customer_info (full_name,age)
values
('Kaustubh Salunkhe',26),
('Kishor Salunkhe',61),
('Manali Salunkhe',49),
('Sayali Salunkhe',29),
('Arnab Debadhikari',28),
('Rohit Divekar',25),
('Amey Chavan',31);
('Hariram Pal', NULL),
('Bipin Rawat',56),
('Kunal Patil', NULL),
('Kiran Salunkhe', NULL),
('Suraj Salunkhe', null);

select * from customer_info;

# 2.Create a python file for the ETL Process. The ETL File has been uploaded in the repo kindly check.
