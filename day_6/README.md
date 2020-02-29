#Day 6

## SQL: (go over if you can for exam)
```ruby
       .:'
   __ :'__   
.'`__`-'__``. \ \        / / | |
:__________.-' \ \  /\  / /__| | ___ ___  _ __ ___   ___
:_________:     \ \/  \/ / _ \ |/ __/ _ \| '_ ` _ \ / _ \
:_________`-;    \  /\  /  __/ | (_| (_) | | | | | |  __/
 `.__.-.__.'      \/  \/ \___|_|\___\___/|_| |_| |_|\___|

```
```css
- Joins
- Subquieries
- Groupby, Orderby, Having
- Aliasing
```

### Some of The Most Important SQL Commands:
```css
* SELECT - extracts data from a database
* UPDATE - updates data in a database
* DELETE - deletes data from a database
* INSERT INTO - inserts new data into a database
* CREATE DATABASE - creates a new database
* ALTER DATABASE - modifies a database
* CREATE TABLE - creates a new table
* ALTER TABLE - modifies a table
* DROP TABLE - deletes a table
* CREATE INDEX - creates an index (search key)
* DROP INDEX - deletes an index
* SP_HELP - details of table.
```
### What is a database:
```css
- Allows you to store information.
- Data is meaningless(raw data), once processed it becomes information which has a purpose.
- A structured set of data head in a computer, especially one that is accessible in various.
- Without a table name, it’s just data not information.
- We must be able to structure tables to contain the right type of information, so that we can query it.
- Rows are called records
- Columns are called attributes.
```
### Terminology
```ruby
Columns -  Database tables are composed of individual columns corresponding to attributes of the object.
Rows - A row consists of one set of attributes corresponding to one instance that a table describes. AKA; records or Tuples.
Tables - A tables predefined format of rows and cloumns that define an entity. AKA; file.
DBMS - A Database Management System allows a computer to perform database functions of storing, adding, retrieving, deleting and modifying data.

Entity stores information of what it is related to. e.g: tables.
```

### Relational SQL vs. Non-Relational NoSQL Databases
```ruby
- There are two main types of databases, relational and non-relational. The major difference between them is how they handle data.
- Relational databases are structured. You have tables and these tables may have dependencies on each other, or relationships. A database for a store will have a table for customers and one for orders. These two tables are related, because an order is made by a customer.
- Non-relational databases are document-oriented. This so called document type storage allows multiple 'categories' of data to be stored in one construct or Document. So using the previous example, a Customer document, would have the customer's information, a sub-category for all their orders, etc.
```

### Keys:
```ruby
- Primary key is a single field or combination of fields that uniquely defines a record. None of the fields that are part of the primary key can contain a NULL value. A table can have only one primary key.
- In SQL, a Candidate key is a column or a set of columns that can qualify as a primary key in the database. There can be multiple candidate keys in a database relation and each candidate can work as a primary key for the table.
- In SQL, a Composite key (can be considered a primary key) is a combination of two or more columns in a table that can be used to uniquely identify each row in the table when the columns are combined uniqueness is guaranteed, but when it taken individually it does not guarantee uniqueness.
- In SQL, A foreign key is a column or group of columns in a relational database table that provides a link between data in two tables.
```

### Types of Databases:
```css
- Flat file database, stores everything in one tables=. Good for small numbers of records related to a single topic.
- Relational database, gives you the acuity to separate  masses of data into numerous tables. They are linked to each other through the use of keys.
- Big Data, MongoDB, Vertical, etc. Used for data analytics and business intelligences , Digital age and internet of things
```
### Relationship types:
```css
- One too one, each row in table A is linked to no more than one row in table B. This is an attributes of the relationship not the tables. A student may have one row in the contact_info table.
- One too many, Each row in the table can be related to many rows in the related table. This allows frequently used information to be saved only once in a table and referenced many times in all other tables.
- Many too many,  one or more rows in a table can be related to 0, 1 or many rows in another table. A 3rd tables called a mapping or link table is required in order to implement such a relationship. For example customers can purchase many products.
```

### Structure Query Language(SQL):
```css
- Data Manipulation Language, (DML): SELECT, INSERT, UPDATE, DELETE.
- Data Definition Language, (DDL): CREATE, ALTER, DROP, TRUNCATE, MODIFY.
- Data Control Language, (DCL): GRANT, REVOKE.
- Transaction Control Language: (TCL), COMMIT, ROLLBACK, SAVEPOINT.

### CHAR VS VARCHAR:
```css
- CHAR is fixed length while VARCHAR is variable length. That means, a CHAR(x) string has exactly x characters in length, including spaces. A VARCHAR(x) string can have up to x characters and it cuts off trailing spaces, thus might be shorter than the declared length.
- In terms of efficiency, if you are storing strings with a wildly variable length then use a VARCHAR, if the length is always the same, then use a CHAR as it is slightly faster.
- They also differ in maximum length where the length of a CHAR value can be any value from 0 to 255 and the maximum length of a VARCHAR value is 65,535.
```

### Variations on INSERT:
```ruby
- Changing the order of the columns
- Omitting column names
- Leaving some columns
```
```python
- VARCHAR, CHAR and DATE ALL USE QUOTES FOR THEIR values.
- An insert statement including DECIMAL and INT does not use any quotes.
```
# __(☞ ͡° ͜ʖ ͡°)☞ ᵗᑋᵃᐢᵏ ᵞᵒᵘ__
