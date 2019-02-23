# EshoppingZone-Project



#First create databases for all services before running.




#Here we have used two types of databases MYSQL,MONGODB.





#Database commands for MYSQL

-->Create database Project_db          /*this database for profile-service*/

--.Create database wallet_service      /*this database for wallet-service*/






#Database Commands for Mongodb

-->Use Product_db                      /* this database for product-service*/

-->Use Demo                            /*this database for Cart-service*/

-->Use Test                            /*this database for Order-service*/






#After that restore the "Product_db" database by the following way

#clone the database file from git repository using following command in git bash

-->git clone https://github.com/EshoppingZone/db_files.git





After that open CMD from MONGODB bin folder and run the command

-->mongorestore -d Product_db (here give the path of database file)





#Now Everything is ready to go.

