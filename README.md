# Command-For-Sotware-Tools

## Postgres

1.Verifying the Installation of PostgreSQL
   
   ps -ef | grep postgres
   
2. start postgres shell 
    
    psql postgres -U postgres (for me)
  
3. command to get a list of all available databases.

     \l
     
4.  Enlisting the available tables in the current database

     \dt

5. Switching to another database
    
     \c <database_name>
 
6.  Describing a particular table
      
    \d <data_table>

7.  Create DataBase
    
    CREATE DATABASE testing;
 
##  big-data-postgresql-and-apache-spark

   1.Create Database and connect to it 
   
      CREATE DATABASE <db_name>;
      
       \c <db_name>
       
    2. Create a table 
        
        CREATE TABLE t1 (id int, name text);
    
    3.  Start Spark Shell
    
         spark-shell
         
    4.   add the PostgreSQL JDBC driver
    
         
    
        
      
