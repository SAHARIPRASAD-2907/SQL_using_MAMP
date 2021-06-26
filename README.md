# MYSQL using MAMP

### Command to connect database with terminal
/Applications/MAMP/Library/bin/mysql -uroot -proot

##### See all databases 
```SQL
SHOW DATABASES;
```

##### Selecting Database
```sql
USE database_name;
````

##### Describing Table
```
describe table_name
```

##### CREATING TABLE EMPLOYEE
```sql
create table employee( Fname VARCHAR(15), Minit CHAR(1), LName VARCHAR(15), SSN INTEGER(10), BDate DATE, Address Varchar(30), Sex CHAR(1), Salary INT(10), SuperSSN INTEGER(10) DEFAULT NULL, DepNo CHAR(1));
```

##### CREATING TABLE MANAGER
```sql
create table Department( Dname VARCHAR(15), DepNo CHAR(1), MgrSSN INT(10), MgeStart DATE);
```

##### CREATING TABLE PROJECT
```sql
create table Project( Pname Varchar(10), pnumber INT(4), Plocation Varchar(20), DepNo CHAR(1));
```
##### INSERTING VALUES INTO PROJECT
```sql
insert into project values( "ProjectA", 3388, "Houston", 1);
insert into project values( "ProjectB", 1945, "Salt lake City", 3);
insert into project values( "ProjectC", 6688, "Houston", 5);
insert into project values( "ProjectD", 2423, "Bellaire", 4);
insert into project values( "ProjectE", 7745, "Sugarland", 5);
insert into project values( "ProjectF", 1566, "Salt lake City", 3);
insert into project values( "ProjectG", 1234, "New York", 2);
```
