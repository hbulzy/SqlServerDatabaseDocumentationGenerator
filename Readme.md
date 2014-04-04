This project will allow you to create human readable documentation for a Microsoft SQL Server database (versions 2005+).  This includes schemas, tables, views, columns, functions, and stored procedures.  

Descriptions for objects are taken from extended properties with a name 'MS_Description' such as those created when descriptions provided to database objects using SQL Management Studio.

To use this project build it using Visual Studio 2012 or later.  Then run the DocumentationGeneratorApplication program providing a connection string to your database and supplying a file name for the resulting documentation file.  The file will be an HTML file.

An example of the resulting documentation file can be viewed at http://jeremykdev.github.io/SqlServerDatabaseDocumentationGenerator/AdventureWorks-sample.html

In addition to creating documentation the application can help you identify objects (tables, views, etc.) without a description in the database metabase and create the SQL script to add descriptions.