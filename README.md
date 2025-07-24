# rock_sql


🧠 SQL is the Brain. BI Tools are the Face.
✔️ SQL lets you talk directly to your database — extract, filter, join, and clean data with full control.
✔️ Power BI / Tableau are great for visualizing and sharing insights — but they depend on clean, structured data.
____________________________________________________________________________________

🚀 Here’s What SQL Unlocks:
✅ Custom Queries – go beyond UI filters
✅ Joins – combine data across multiple tables
✅ Data Cleaning – fix missing values, remove duplicates
✅ Performance – query only what you need
✅ Automation – schedule and reuse SQL scripts
✅ Better Control – especially with large datasets
____________________________________



/*
Enter your query here.
*/

-- students => Id, Name,marks 

-- Grade => Grade, min_mark , max_Mark

-- grade lower than 8 
-- order by desc grade 

-- 8-10 => order by name



1. 2025 - 07 - 18
   https://www.kaggle.com/datasets/smayanj/e-commerce-transactions-dataset



   use sql_course;

create table if not exists person(
personid int, 
firstname varchar(30) ,
address varchar(50)
);

insert into person(personid,firstname,address) 
values(1,"lokesh",'xyz'),
      (2,'rishank','abc');
      
select * from person 

-- change table structure 
describe person;

-- change table name 
rename table person to persons;

describe persons;

alter table persons rename to persons1;

-- add new column 
alter table persons1 add column lastname varchar(30);

describe persons1;
select * from persons1;

-- rename exitsting column 
alter table persons1 rename column lastname to last_name;

-- drop existing column 
alter table persons1 drop column last_name;

-- again crated two columns 
alter table persons1 add column lastname varchar(30); 
alter table persons1 add column created_at datetime ;

                    





