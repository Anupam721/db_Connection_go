# db_Connection_go
Simple, working code to connect and send queries to a DB and retrieve results. Uses golang

# Env setup (ubuntu)
1. Install go.
2. Install mysql (I used DigitalOcean guide)
3. Setup database users and passwords.
4. Log into database.(in my case I created a separate user and password and didnt use root user for creating DB)
5. Once in mysql cmd prompt, run the following :
    a. create database recordings;
    b. use recordings;
    c. source /path/to/create-tables.sql
6. In above step, db recordings is created and a table is created and filled with data.
7. Execute "go run ." in project folder.
