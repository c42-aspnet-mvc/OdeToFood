EF model and seed data updated

PM> Update-Database -Verbose
Using StartUp project 'OdeToFood'.
Using NuGet project 'OdeToFood'.
Specify the '-Verbose' flag to view the SQL statements being applied to the target database.
Target database is: 'OdeToFoodDb' (DataSource: (LocalDb)\MSSQLLocalDB, Provider: System.Data.SqlClient, Origin: Configuration).
No pending code-based migrations.
Unable to update database to match the current model because there are pending changes and automatic migration is disabled. Either write the pending model changes to a code-based migration or enable automatic migration. Set DbMigrationsConfiguration.AutomaticMigrationsEnabled to true to enable automatic migration.
You can use the Add-Migration command to write the pending model changes to a code-based migration.

## At this point set "AutomaticMigrationsEnabled = true;" in Configuration and command run again

PM> Update-Database -Verbose
Using StartUp project 'OdeToFood'.
Using NuGet project 'OdeToFood'.
Specify the '-Verbose' flag to view the SQL statements being applied to the target database.
Target database is: 'OdeToFoodDb' (DataSource: (LocalDb)\MSSQLLocalDB, Provider: System.Data.SqlClient, Origin: Configuration).
No pending code-based migrations.
Applying automatic migration: 201808081017141_AutomaticMigration.
ALTER TABLE [dbo].[RestaurantReviews] ADD [ReviewerName] [nvarchar](max)
[Inserting migration history record]
Running Seed method.