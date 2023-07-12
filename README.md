# Hibernate-CRUD-operation-Library-
This hibernate project helps to use the basic (insert, retrieve, update, delete) operations on Table Library with three fields (bno,bname and pages).
Process:
Create a database (here taken Section64) and use that database in MySQL.
a. Create a Maven Project and add dependencies such as mysql , hibernate core and lombok into pom.xml (already done in the folder). Save the file
b. Go to Market place in eclipse IDE and install JBoss 
b. create a hibernate.cfg.xml file to hold all the configuration parameters. This to be placed under src folder
c. Create a Model class Library with the three fields, create getters, setters and toString() method. Use @Entity and @Id annotations to automatically generate table and primary key respectively
d. create a Main class. Here, create an object to SessionFactory, Session, Transaction and perform the basic operations

