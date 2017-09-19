# NorthWind
## Introduction:
NorthWind is MS created DB schema for SQL demonstration, original NorthWind is deposite at https://northwinddatabase.codeplex.com/, but this will be terminated soon, so it is worth to make a backup here.

## Reference
1. http://www.bradoncode.com/tutorials/learn-mean-stack-tutorial/ 
2. https://github.com/tmcnab/northwind-mongo
  Convert from SQL to CSV then mongoDB
3. https://github.com/dalers/mywind <== Converted to mysql format (Worked for me)
4. 

## DB Schema
   ![Alt](/images/Northwind.png "Title")
   
## https://northwinddatabase.codeplex.com/releases/view/71634
Northwind.bak.zip - Northwind database backup for Sql Server 2005 and 2008.
Unzip / decompress the file then use the Restore Database option from Sql Server Management Studio 2005 / 2008 to restore the database

Northwind.sql.zip - - Northwind database creation script for Sql Server 2005 and 2008.
Create a database called northwind in your Sql Server then.
Unzip / decompress the file then open the sql file in Sql Server Management Studio 2005 / 2008 and hit F5.
OR
run the below command (sample)
sqlcmd -S Localhost -d Northwind -i D:\Sql\Northwind.sql
