![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome Claudia, 


-- install the database
wget https://raw.githubusercontent.com/lerocha/chinook-database/master/ChinookDatabase/DataSources/Chinook_PostgreSql.sql

-- launch the postres CLI
set_pg
psql

--list of DB
\l

-- create DB
CREATE DATABASE chinook;

--switch between DBs
\c nameofthedb

--install postgreSQL
\i Chinook_PostgreSql.sql

--quit
\q

--start the server and tell it to which db we want to connect
psql -d chinook

--display tables on the db
\dt

--install psycopg2
pip3 install psycopg2

--create a file
touch nameofthefile
---

Happy coding!
