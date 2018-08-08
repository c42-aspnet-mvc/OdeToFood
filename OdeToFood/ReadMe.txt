EF commands run in this code change

PM> Enable-Migrations -ContextTypeName OdeToFoodDb
Checking if the context targets an existing database...
Detected database created with a database initializer. Scaffolded migration '201808080929382_InitialCreate' corresponding to existing database. To use an automatic migration instead, delete the Migrations folder and re-run Enable-Migrations specifying the -EnableAutomaticMigrations parameter.
Code First Migrations enabled for project OdeToFood.

PM> Update-Database -Verbose
Using StartUp project 'OdeToFood'.
Using NuGet project 'OdeToFood'.
Specify the '-Verbose' flag to view the SQL statements being applied to the target database.
Target database is: 'OdeToFoodDb' (DataSource: (LocalDb)\MSSQLLocalDB, Provider: System.Data.SqlClient, Origin: Configuration).
No pending code-based migrations.
Running Seed method.
 