# trafficfinemanagement

trafficfinemanagement
This is a simple DBMS project to implement a Frontend and Backend framework for developing a website to add violations, pay penalties(For law enforcers and vehicle owners) and View statistics and make changes to database to administartors.

Steps to Run the project:

Step 1: In your SQL=> source 1.Traffic_fine_Database.sql

Step 2: In your SQL=> source 2.Create_roles.sql

Step 3: Open terminal and run python 3.Insert.py

Step 4: In your SQL=> source 4.Insert_Zone_Details.sql

Step 5: In your SQL=> source 5.Insert_Foreign_Keys.sql

Step 6: In your SQL=> source 6.Create_Triggers.sql

Step 7: In your SQL=> source 7.Procedure.sql

Step 8: In your SQL=> source 8.Function.sql

Step 9: Open terminal and run app.py

Step 10:Open another terminal and run admin.py

Note : While Inserting into the violation table Only those vehicle present in the database will be allowed to insert therefore execute ‘SELECT * from rto_vehicle LIMIT 30’ and then add violations of vehicle that appear from the rto_database
