# Learning SQL Reference Guide

This repository is meant to be a reference of materials to learn all about [SQL](https://en.wikipedia.org/wiki/SQL).  This can be used by folks who are new to to the data space and/or SQL altogether and seasoned professionals to brush up on things, or provide additional materials for junior folks to use to learn. 

__Note: This is largely biased towards SQL Server, as this is where most of my knowledge converges to, however most of these concepts are portable to other RDBMS's such as Oracle, MySQL.  The SQL code itself, if written in its [ANSI](https://blog.ansi.org/sql-standard-iso-iec-9075-2023-ansi-x3-135/#gref) form is also portable to databases of all flavors such as Amazon Redshift, Google BigQuery, Databricks SQL (Although, the latter is not really a database, but I hope you get my point!).__

## The SQL Syllabus

### Relational Database Concepts
- [Relational Database Concepts](https://www.upi.pr.it/docs/easfg/easvrfgp7.htm)
- [SQL Server Primary Keys](https://www.sqlservertutorial.net/sql-server-basics/sql-server-primary-key/)
- [What is a foreign key in SQL Server?](https://www.sqlshack.com/what-is-a-foreign-key-in-sql-server/)
- [Star Schema in Data Warehousing](https://www.geeksforgeeks.org/star-schema-in-data-warehouse-modeling/)
- [Grain](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/grain/)
- [Declaring the Grain](https://www.kimballgroup.com/2003/03/declaring-the-grain/)

### Relational Database Objects
- [Instance](https://pediaa.com/what-is-the-difference-between-instance-and-database-in-sql-server/)
- [Database](https://learn.microsoft.com/en-us/sql/relational-databases/databases/databases?view=sql-server-ver16)
- [Schema](https://www.sqlshack.com/a-walkthrough-of-sql-schema/)
- [Table](https://learn.microsoft.com/en-us/sql/relational-databases/tables/tables?view=sql-server-ver16)
- [View](https://learn.microsoft.com/en-us/sql/relational-databases/views/views?view=sql-server-ver16)
- [Stored Procedure](https://www.sqlshack.com/sql-server-stored-procedures-for-beginners/)
- [Functions](https://www.sqlshack.com/use-sql-server-built-functions-create-user-defined-scalar-functions/)

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
- [SQL Sevrer Temporary Tables](https://www.sqlservertutorial.net/sql-server-basics/sql-server-temporary-tables/)
- [Overview and Performance Tips of Temp Tables in SQL Server](https://www.sqlshack.com/overview-and-performance-tips-of-temp-tables-in-sql-server/)
- [Temporary Tables in SQL Server](https://www.red-gate.com/simple-talk/databases/sql-server/t-sql-programming-sql-server/temporary-tables-in-sql-server/)
- [Advanced SQL Tutorial | Temp Tables](https://www.youtube.com/watch?v=RF0LE3hYFrI)

#### DML - Selecting Data - Using Common Tabe Expressions (CTEs)
- [SQL Server CTE](https://www.sqlservertutorial.net/sql-server-basics/sql-server-cte/)
- [WITH common_table_expression - TransactSQL](https://learn.microsoft.com/en-us/sql/t-sql/queries/with-common-table-expression-transact-sql?view=sql-server-ver16)
- [CTE in SQL Server Examples](https://www.mssqltips.com/sqlservertip/6861/cte-in-sql-server-examples/)
- [Advanced SQL Tutorial | CTE (Common Table Expressions)](https://www.youtube.com/watch?v=K1WeoKxLZ5o)
- [SQL Server CTE vs Temp Table vs Table Variable Performance Test](https://www.mssqltips.com/sqlservertip/5118/sql-server-cte-vs-temp-table-vs-table-variable-performance-test/)

#### DML - Selecting Data - The UNION, UNION ALL, EXCEPT, INTERSECT operators
- [SQL Union overview, usage and examples](https://www.sqlshack.com/sql-union-overview-usage-and-examples/)

#### DML - Selecting Data - Windowing
- [Window Functions – A Must-Know Topic for Data Engineers and Data Scientists](https://www.analyticsvidhya.com/blog/2020/12/window-function-a-must-know-sql-concept/)
- [The Ultimate Guide to SQL Window Functions](https://www.stratascratch.com/blog/the-ultimate-guide-to-sql-window-functions/)
- [How to Use Window Functions in SQL – with Example Queries](https://www.freecodecamp.org/news/window-functions-in-sql/)

#### DML - Finding Duplicates
- [How To Find Duplicate Values in SQL](https://learnsql.com/blog/how-to-find-duplicate-values-in-sql/)
- [Two Best Tricks to Finding Duplictaes in SQL](https://towardsdatascience.com/2-best-sql-tricks-to-find-duplicate-values-in-a-table-1197618dcc74)


#### DML - Inserting Data
- [INSERT INTO VALUES](https://www.w3schools.com/sql/sql_insert.asp)
- [INSERT INTO SELECT](https://www.w3schools.com/sql/sql_insert_into_select.asp)
- [Inserting Data into Sql Server](https://www.tutorialsteacher.com/sqlserver/insert-data)
- [SELECT INTO](https://www.w3schools.com/sql/sql_select_into.asp)

#### DML - Updating data
- [SQL Update Statement](https://www.w3schools.com/sql/sql_update.asp)
- [SQL Server Update](https://www.sqlservertutorial.net/sql-server-basics/sql-server-update/)

#### DML - Deleting data
- [Delete in SQL](https://www.simplilearn.com/tutorials/sql-tutorial/delete-in-sql)

#### DML - Merging data
- [Understanding the SQL Merge Statement](https://www.sqlshack.com/understanding-the-sql-merge-statement/)
- [SQL Server Merge](https://www.sqlservertutorial.net/sql-server-basics/sql-server-merge/)
- [Using MERGE in SQL Server to insert, update and delete at the same time](https://www.mssqltips.com/sqlservertip/1704/using-merge-in-sql-server-to-insert-update-and-delete-at-the-same-time/)

### Data Defintion Language (DDL)

#### DDL - CREATE/ ALTER/ DROP/ TRUNCATE
- [SQL DDL: Getting started with SQL DDL commands in SQL Server](https://www.sqlshack.com/sql-ddl-getting-started-with-sql-ddl-commands-in-sql-server/)


## Common Mistakes
- [SQL Errors: Five Common SQL Mistakes](https://learnsql.com/blog/five-common-sql-errors/)
- [10 Common SQL Programming Mistakes](https://www.red-gate.com/simple-talk/databases/sql-server/t-sql-programming-sql-server/ten-common-sql-programming-mistakes/)
- [7 Must Know SQL Querying Mistakes & Fixes](https://towardsdatascience.com/7-must-know-sql-querying-mistakes-fixes-321ee292a251)
- [5 Most Common SQL Mistakes to Avoid](https://towardsdatascience.com/5-most-common-sql-mistakes-you-should-avoid-dd4eb4088f0c)

## Query Optimization
- [Query Optimization Overview](https://www.sqlshack.com/query-optimization-techniques-in-sql-server-tips-and-tricks/)
- [A Detailed Guide on SQL Query Optimization](https://www.analyticsvidhya.com/blog/2021/10/a-detailed-guide-on-sql-query-optimization/)


## Additional Sources

### Reccomended Books
- [Exam Ref 70-761 Querying Data with Transact-SQL](https://www.amazon.com/Exam-70-761-Querying-Data-Transact-SQL-ebook/dp/B06Y21QGGQ/ref=sr_1_3?crid=UF30TC6TDGTR&keywords=querying+transact+sql&qid=1687891036&s=books&sprefix=querying+transact+sql%2Cstripbooks%2C68&sr=1-3)
- [SQL QuickStart Guide: The Simplified Beginner's Guide to Managing, Analyzing, and Manipulating Data With SQL](https://www.amazon.com/SQL-QuickStart-Guide-Simplified-Manipulating/dp/1945051752/ref=zg_bs_g_3804_sccl_1/142-9099606-5642665?psc=1)
- [T-SQL Querying (Developer Reference)](https://www.amazon.com/T-SQL-Querying-Developer-Reference-Ben-Gan/dp/0735685045/ref=zg_bs_g_3804_sccl_16/142-9099606-5642665?psc=1)
- [Building the Data Warehouse](https://www.amazon.com/Building-Data-Warehouse-W-Inmon/dp/0764599445/ref=sr_1_19?crid=VVAP5AO7ZNBC&keywords=bill+inmon&qid=1687891140&s=books&sprefix=bill+inmon%2Cstripbooks%2C74&sr=1-19)
- [Beginning SQL Joes 2 Pros: The SQL Hands-On Guide for Beginners](https://www.amazon.com/Beginning-SQL-Joes-Pros-Hands/dp/143925317X)

### Reccomended Courses
- [Querying Microsoft SQL Server with Transact-SQL](https://www.udemy.com/course/70-461-session-2-querying-microsoft-sql-server-2012/?ranMID=39197&ranEAID=JVFxdTr9V80&ranSiteID=JVFxdTr9V80-17MjWt7PdeK4ftPdH_1cLw&LSNPUBID=JVFxdTr9V80&utm_source=aff-campaign&utm_medium=udemyads)
