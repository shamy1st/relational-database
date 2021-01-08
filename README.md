# Relational Database


--                      | MySQL                                 | Oracle                                  | PostgreSQL         | MS SQL Server
------------------------|---------------------------------------|-----------------------------------------|--------------------|--------------
Definition              | It is an open-source, cross-platform relational database management system built by Swedish Company MYSQL AB and currently supported by the Oracle. | Oracle is a relational database system (RDBMS) that implements object-oriented features. It allows to store and retrieve data quickly and safely. It can handle a large amount of data. | PostgreSQL is an open-source, cross-platform, and object-relational database management system (ORDBMS) built in the computer science department, University of California. | It is a type of RDBMS database software, which is mainly developed for the Windows system to store, retrieve, and access data requested by the developer.
Release                 | 1995                                  | 1980                                    | 1995               | 1989
License                 | Free, Open-source (Licensed GNU)      | Licensed, Free Express Edition          | Licensed MIT-style, Open-source | Licensed Microsoft
Implementation Language | C/C++                                 | Assembly, C/C++                         | C                  | C++
GUI Tool                | MySQL Workbench                       | Oracle SQL Developer                    | PgAdmin            | SQL Server Management Studio (SSMS)
OS Support              | All                                   | Windows, Mac, Linux, Unix, z/OS         |                    | Windows, Mac, Linux
Scale                   | Small, Large                          | Very Large                              |
Language Support        | Only SQL                              | SQL, PL/SQL                             | SQL, NoSQL         | 
Data Partitioning       | No                                    | Yes                                     | 
Security                | username, password, host to access db | username, password, profile validation to access db | 
Security                | TLS support                           |                                         | Native SSL support | 
System Type             | Static System                         | Static, Dynamic Systems                 | 
Null Value              | Supported                             | Not Supported                           | 
Characters              | CHAR, VARCHAR                         | CHAR, VARCHAR2, NCHAR, NVARCHAR2        | 
Backup Mechanism        | mysqlhotcopy, mysqldump               | backup, hot backup, import, export, ... | 
XML Support             | Not Supported                         | Supported                               | 
Locking                 | Only Table Locking                    | Table Locking, Row locking              | 
Storage Features        | tablespace, synonym, packages, ...    | tablespace, synonym, packages, ...      | 
Storage Engine          | multi-layer structure, set of storage engines (e.g. InnoDB, MyISAM) |           | unified database server, single storage engine | 
ACID Compliance         | Only some versions are ACID-compliant |                                         | Complete Support    | 
Main Focus              | Speed                                 |                                         | Features, Standards | 
Operations Complexity   | For Simple operations                 |                                         | For Large, Complex operations | 
Table Inheritance       | Not Supported                         |                                         | Supported           | 
Replication             | Asynchronous, Synchronous, Semi-synchronous |                                   | Asynchronous, Synchronous, Cascade | 
Task Scheduler          | Scheduled Event                       |                                         | pgAgent Task Scheduler | 
Connection Scalability  | OS thread per connection creation     |                                         | OS process per connection creation | 
Company Uses            | GitHub, US Navy, NASA, Tesla, Netflix, Facebook, Twitter, Zappos, YouTube, Spotify, Amazon, Uber Technologies, Dropbox, Pinterest, Airbnb |  | Apple, Etsy, IMDB, Macworld, Debian, Red Hat, Sun Microsystem, Cisco, Skype | Microsoft, Stack Exchange, Intuit, MIT, Hepsiburada, PedidosYa

## Oracle vs MySQL

### Oracle advantages over MySQL

* PostgreSQL is a very secure, independent, and feature-rich open-source database.
* PostgreSQL supports a lot of advanced data types like multi-dimensional arrays, user-defined types, etc.
* PostgreSQL follows the SQL standards very well and supports "advanced" SQL stuff like window functions or common table expressions.
* It provides all performance optimization that is supported in Oracle and SQL Server.
* PostgreSQL is using by companies like Amazon, Redshift, Instagram, etc.

### MySQL advantages over Oracle

* MySQL is more popular than PostgreSQL in terms of DB ranking.
* Getting community support and search answers is easier in MySQL than PostgreSQL.
* Replication is well implemented in MySQL rather than PostgreSQL.
* MySQL is using by companies like Facebook, Twitter, Pinterest, etc.

## PostgreSQL vs MySQL

### PostgreSQL advantages over MySQL

### MySQL advantages over PostgreSQL


## MS SQL Server vs MySQL

### MS SQL Server advantages over MySQL

### MySQL advantages over MS SQL Server


## Ref
* https://www.javatpoint.com/mysql-vs-oracle
* https://www.javatpoint.com/postgresql-vs-mysql
* https://www.javatpoint.com/mysql-vs-ms-sql-server
