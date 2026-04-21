# Install MySQL and DataGrip

**Deadline**: Before next week. 

--- 

## MySQL

MySQL is the database that we will use in Tech 1, programming and your 1st year project.

**Important**: Make sure to remember your root password! This is crucial to be able to access the database.

**Success criteria**: Open your terminal and execute the command: `mysql --version`.

Alternatively, if you are on Windows see if you can open the program `MySQL Shell`.

**Second success criteria**: You should be able to connect to the MySQL server and run `SHOW DATABASES`.

---

### Windows

You can download the [Community installer here](https://dev.mysql.com/downloads/installer/).

Click this if you need a visual [tutorial](https://www.geeksforgeeks.org/mysql/how-to-install-mysql-in-windows/).

Maybe this [Alternative tutorial](https://www.datawithbaraa.com/sql-introduction/download-install-mysql/) helps you catch something you missed in the first one.

After following any of the guides, run `"MySQL Command Line Client`.

You can now run `SHOW DATABASES;`.

---

### MacOS

https://www.geeksforgeeks.org/installation-guide/how-to-install-mysql-on-macos/

After following the guide, add MySQL to path so that you can access it from anywhere:

```bash
$ export PATH="/usr/local/mysql/bin:$PATH" >> ~/.zshrc
```

Now try the following and enter your password:

```bash
$ mysql -u root -p
```

You can now run `SHOW DATABASES;`.

---

## DataGrip

DataGrip is a product by JetBrains for Databases. The benefit of using it, is that you will be able to transfer all the knowledge to set up databases in IntelliJ and have databases connected to your code projects there. 

[Install DataGrip](https://www.jetbrains.com/datagrip/)

Remember to use your EK mail to get your license.

