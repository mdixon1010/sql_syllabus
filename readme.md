# Learning SQL Reference Guide

This repository is meant to be a reference of materials to learn all about [SQL](https://en.wikipedia.org/wiki/SQL).  This can be used by folks who are new to to the data space and/or SQL altogether and seasoned professionals to brush up on things, or provide additional materials for junior folks to use to learn. 

Note: This is largely biased towards SQL Server, as this is where most of my knowledge converges to, however most of these concepts are portable to other RDBMS's such as Oracle, MySQL.  The SQL code itself, if written in its [ANSI](https://blog.ansi.org/sql-standard-iso-iec-9075-2023-ansi-x3-135/#gref) form is also portable to databases of all flavors such as Amazon Redshift, Google BigQuery, Databricks SQL (Although, the latter is not really a database, but I hope you get my point!).

## The SQL Syllabus

### Relational Database Concepts
- [Relation Database Concepts](https://www.upi.pr.it/docs/easfg/easvrfgp7.htm)
- [SQL Server Primary Keys](https://www.sqlservertutorial.net/sql-server-basics/sql-server-primary-key/)
- [What is a foreign key in SQL Server?](https://www.sqlshack.com/what-is-a-foreign-key-in-sql-server/)

### Data Manipulation Language (DML)

#### DML - Selecting Data - Basics

- [SQL Server SELECT Examples](https://www.mssqltips.com/sqlservertip/6818/sql-select-examples/)
- [Table Basics](https://www.sqlcourse.com/beginner-course/table-basics/)
- [The SQL SELECT Statement](https://www.w3schools.com/sql/sql_select.asp#:~:text=The%20SQL%20SELECT%20Statement,%2C%20called%20the%20result%2Dset.)

#### DML - Selecting Data - Using Distinct
- [SELECT DISTINCT](https://www.w3schools.com/sql/sql_distinct.asp)
- [More Examples](https://www.mssqltips.com/sqlservertip/6810/sql-select-distinct-examples/)
- [COUNT() function with distinct clause](https://www.w3resource.com/sql/aggregate-functions/count-with-distinct.php)
- [SQL Server 2019 APPROX_COUNT_DISTINCT Function](https://www.mssqltips.com/sqlservertip/5842/sql-server-2019-approxcountdistinct-function/)

#### DML - Selecting Data - Using Alias
- [SQL Aliases](https://www.w3schools.com/sql/sql_alias.asp)

#### DML - Selecting Data - Using Order By
- [SQL Order By](https://www.w3schools.com/sql/sql_orderby.asp)

#### DML - Selecting Data - The WHERE Clause 
- [Exploring the SQL WHERE statement](https://www.sqlshack.com/exploring-the-sql-where-statement/)
- [Combining and Negating Conditions with AND, OR, and NOT](https://www.peachpit.com/articles/article.aspx?p=1276352&seqNum=6)

#### DML - Selecting Data - The JOIN Operator 
- [An overview of SQL Join types with examples](https://blog.quest.com/an-overview-of-sql-join-types-with-examples/)
- [A step-by-step walkthrough of SQL Inner Join](https://www.sqlshack.com/a-step-by-step-walkthrough-of-sql-inner-join/)
- [SQL Outer Joins](https://mode.com/sql-tutorial/sql-outer-joins/)

#### DML - Selecting Data - Using Group By
- [SQL Group By](https://www.sqltutorial.org/sql-group-by/)
- [GROUP BY - Transact-SQL](https://learn.microsoft.com/en-us/sql/t-sql/queries/select-group-by-transact-sql?view=sql-server-ver16)

#### DML - Selecting Data - Using Having
- [SQL Server Having Clause](https://www.sqlservertutorial.net/sql-server-basics/sql-server-having/)
- [SQL Server Having vs. Where](https://www.sqltutorial.org/sql-having/)

#### DML - Selecting Data - Using Sub Queries
- [SQL Server Subquery Examples](https://www.mssqltips.com/sqlservertip/6036/sql-server-subquery-example/)
- [How to write subqueries in SQL](https://www.sqlshack.com/how-to-write-subqueries-in-sql/)
- [The Ultimate Guide to SQL Server Subqueries](https://www.sqlservertutorial.net/sql-server-basics/sql-server-subquery/)

#### DML - Selecting Data - Using Correlated Sub Queries
- [SQL Correlated Subqueries](https://www.sqltutorial.org/sql-correlated-subquery/)
- [SQL Server Correlated Subqueries](https://www.sqlservertutorial.net/sql-server-basics/sql-server-correlated-subquery/)

#### DML - Selecting Data - Using Temp Tables

#### DML - Selecting Data - Using Common Tabe Expressions (CTEs)

#### DML - Selecting Data - The UNION, UNION ALL, EXCEPT operators

#### DML - Selecting Data - Windowing
-[Window Functions – A Must-Know Topic for Data Engineers and Data Scientists](https://www.analyticsvidhya.com/blog/2020/12/window-function-a-must-know-sql-concept/)

#### DML - Inserting Data

#### DML - Updating data

#### DML - Deleting data

#### DML - Merging data

### Data Defintion Language (DDL)

#### DDL - CREATE/ ALTER/ DROP/ TRUNCATE
- [SQL DDL: Getting started with SQL DDL commands in SQL Server](https://www.sqlshack.com/sql-ddl-getting-started-with-sql-ddl-commands-in-sql-server/)