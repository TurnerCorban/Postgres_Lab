# Software Design Construction Lab 3: PostgreSQL

* Download PostgreSQL at https://www.enterprisedb.com/downloads/postgres-postgresql-downloads and install
* Run pgAdmin 4
* Create the database
  * In the left sidebar, expand servers
  * Expand PostgreSQL 18
  * Right click on Databases > Create > Database...
  * Name the database testdb
  * Save
* Create the test user
  * Right click on Login/Group Roles > Create > Login/Group Role...
  * Name the user Testuser
  * Click on Definition tab
  * Set the password to 123
  * Save
* Build:
```shell
.\gradlew build
```
* Then run: 
```shell
.\gradlew run
```

## Lab Document: ##

| High Level Purpose Statement: | I want to learn how to create a Java program that uses PostgreSQL as a database.                                                                                                                                                              |
|:------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Experimental Design           | For this lab I will follow the guide at https://www.tutorialspoint.com/postgresql/postgresql_java.htm to create a Java program that uses PostgreSQL.                                                                                          |
| Resources Available           | The tutorialspoint guide is a starting point. I can supplement it with the official PostgreSQL documentation. There are also multiple w3schools guides for different aspects of the tool.                                                     |
| Time Estimate:                | I believe this project will take about 4 hours.                                                                                                                                                                                               |
| Experiment Notes:             | My time estimate was pretty accurate. I used Gradle for this project, making it simple to add PostgreSQL as a dependency. When gradlew build runs, it downloads the PostgreSQL driver that allows the Java program to connect to the server.  | 
| Results:                      | Created a Postgres database hosted locally. Created a Java program that connects to the database and runs SQL operations on it.                                                                                                               |
| Consequences for the Future:  | PostgreSQL is becomming a default choice for many SQL databases, with most companies moving away from Oracle.                                                                                                                                 |



