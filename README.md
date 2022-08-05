# Challenge-8
## Movies-ETL
In this assignment, the objective was to extract data from csv and json files, clean them up and merge them, and then put them up on PostgresSql. I ran into many
errors in this assignment as it was quite technically challenging. Most of the code presented in class worked as presented until I got to trying to upload the data on to Sql. The ratings
table appeared to have many more row entries than it was supposed to, so I read about how to communicate directly with the engine and ensure that it did not make
duplicate values.

https://docs.sqlalchemy.org/en/14/core/connections.html
https://stackoverflow.com/questions/34322471/sqlalchemy-engine-connection-and-session-difference
https://www.tutorialspoint.com/python_data_access/python_mysql_cursor_object.htm
