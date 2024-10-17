0x00. MySQL Advanced
Description
This project covers advanced MySQL concepts including creating tables with constraints, optimizing queries with indexes, and implementing stored procedures, functions, views, and triggers in MySQL.
Learning Objectives
By the end of this project, you should be able to explain:

How to create tables with constraints
How to optimize queries by adding indexes
What are and how to implement stored procedures and functions in MySQL
What are and how to implement views in MySQL
What are and how to implement triggers in MySQL

Requirements
General

All files executed on Ubuntu 18.04 LTS using MySQL 5.7 (version 5.7.30)
All files should end with a new line
All SQL queries should have a comment just before them
All files should start with a comment describing the task
All SQL keywords should be in uppercase (SELECT, WHERE…)
The length of files will be tested using wc

Tasks
Mandatory Tasks

We are all unique! - Write a SQL script that creates a table users with unique email and id
In and not out - Create a table users with enumerated country values
Best band ever! - Rank country origins of bands by number of fans
Old school band - List Glam rock bands by longevity
Buy buy buy - Create a trigger to decrease quantity after adding new order
Email validation to sent - Create a trigger for email validation
Add bonus - Create a stored procedure AddBonus
Average score - Create a stored procedure ComputeAverageScoreForUser
Optimize simple search - Create an index on the first letter of name
Optimize search and score - Create an index on the first letter of name and score
Safe divide - Create a function SafeDiv
No table for a meeting - Create a view need_meeting

Advanced Tasks

Average weighted score - Create stored procedure ComputeAverageWeightedScoreForUser
Average weighted score for all! - Create stored procedure ComputeAverageWeightedScoreForUsers

Usage
bash
# Import SQL dump
$ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
$ curl [dump_url] -s | mysql -uroot -p hbtn_0d_tvshows

# Execute SQL script
$ cat [script_name].sql | mysql -uroot -p [database_name]

AUTHOR 
[Olowookere Busayomi]
