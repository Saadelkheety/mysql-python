# mysql-python
## Guidelines
  - Do not hardcode the values needed to connect and log into the databas
  - Any application that accepts input must expect to handle bad data  - “SQL injection” attack -.
  - fetchmany() is the general-purpose method when you cannot predict the size of the result set : you keep calling it and looping through the returned items, until there are no more results to process.
  - https://dev.mysql.com/doc/refman/8.0/en/optimization.html
  
  _________________________________
  for mysql to work fine with python after installing mysql-server make sure to install :
  ```
  sudo apt-get install mysql-server
  sudo apt-get install python3.6-dev 
  sudo apt-get install mysql-client
  sudo apt-get install libsqlclient-dev libmysqld-dev
  sudo apt-get install libssl-dev
  
  pip3 install mysqlclient
  ```
for mariadb to work fine with python after installing mariadb-server make sure to install :
```
yum install python-devel mariadb-server
yum install mariadb-devel
pip3 install mysqlclient
```
