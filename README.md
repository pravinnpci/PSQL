##psql##
hi pravin

praveen psql
hi
 sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs) -pgdg main" > /etc/apt/sources.list.d/pgdg.list'

curl -fsSL https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo gpg--dearmor-o /etc/apt/trusted.gpg.d/postgresql.gpg



CREATE USER <your_username> WITH PASSWORD '<your_password>';
CREATE USER pravin with password pravin123;
 CREATE DATABASE pravinsql;

  GRANT ALL PRIVILEGES ON DATABASE pravinpsql TO pravin;

 CREATE TABLE customer (
 customer_id SERIAL PRIMARY KEY,
 name VARCHAR(100) NOT NULL,
 email VARCHAR(150) UNIQUE NOT NULL
 );


INSERT INTO customer (name, email)
 VALUES
 ('John Doe', 'john.doe@example.com'),
 ('Jane Smith', 'jane.smith@example.com');

 INSERT INTO customer (name, email)
 VALUES
 ('John Doe', 'john.doe@example.com'),
 ('Jane Smith', 'jane.smith@example.com');

 postgres@codespaces-79b93e:/workspaces/PSQL$ psql -d pravin -d pravinpsql -W

 


 
