# northwind-database-practice

I have used this database to practice some basic sql queries. The Query Questions I have used for practising the queries are in as Northwind_Database_Query_Questions.docx

[Northwind_Database_Query_Questions]: ./Northwind_Database_Query_Questions.docx	"Northwind_Database_Query_Questions"

 and answers/queries are in the Northwind_Database_Query_Answers.docx

[Northwind_Database_Query_Answers]: ./Northwind_Database_Query_Answers.docx	"Northwind_Database_Query_Answers"

 file.

The schema for Northwind Database can be found Northwind_schema.pdf

[Northwind schema]: ./Northwind_Schema.pdf	"here"



#### Steps to work on Northwind Database:

##### Importing the existing .sql file in mysql server

1. First, log in to MySQL as **root** or another user with sufficient privileges to create new databases:

   `mysql -u root -p`

2. This command will bring you into the MySQL shell prompt. Next, create a new database with the following command. In this example, the new database is called `northwind`:

   `CREATE DATABASE northwind;`

3. Then exit the MySQL shell by pressing `CTRL+D`. From the normal command line, you can import the dump file with the following command:

   `mysql -u username -p northwind < northwind_mysql.sql`

4. Use Northwind database for your operations.

   `USE northwind;`



NOTE: Please add your custom built queries in the respective files. It might prove helpful for those starting out for SQL programming.

