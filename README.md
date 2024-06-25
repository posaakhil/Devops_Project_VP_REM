# Prerequisites

- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

# Technologies 

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

# Database

In this project, MySQL is used as the database.

### MySQL Installation Steps for Ubuntu 14.04:

1. Update your package index:
   ```bash
   sudo apt-get update

Install the MySQL server package:
bash

sudo apt-get install mysql-server
Importing MySQL Database Dump:
After installing MySQL, follow these steps to import the database dump (accountsdb.sql) into your MySQL server:


This will install MySQL server on your system.

# Importing MySQL Database Dump

After installing MySQL, you can import a MySQL database dump (`accountsdb.sql`) into your MySQL server:

1. Locate the SQL dump file in your project directory:


2. Use the following command to import the dump into MySQL (replace `<user_name>` with your MySQL username and `accounts` with your database name):


This command will import the database structure and data from `accountsdb.sql` into your MySQL database named `accounts`.



