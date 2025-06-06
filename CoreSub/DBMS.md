🟢1. What is DBMS? Mention its advantages.
```
     A DBMS is a software that helps to store , manage, and organize data is a structured way , 
     allowing users to easily access update and delete data from a database.

    Advantages of DBMS 
        Data Security – Keeps data safe from unauthorized access.
        Data Sharing – Multiple users can access data at the same time.
        Data Integrity – Ensures accuracy and consistency of data.
        Backup and Recovery – Automatically saves and restores data.
        Reduces Data Redundancy – Avoids storing the same data multiple times.
        Easy Data Access – Simple to search, update, or delete data.
        ```


🟢2. What is a Database?
```
    A database is a organized collection of data that can be easily accessed, managed, and updated.
    ```

🟢3. Define a Database System.
```
    A Database System is a combination of the database, DBMS , and the applications used 
    to access and manage the data.
    ```

🟢4. What is RDBMS? Mention its properties.
```
    RDBMS stand for Relational Database Management System
    RDBMS is a type of DBMS that stores data in tables (rows and columns) and uses relationships between them.

    Properties of RDBMS:
        Tables – Data is stored in rows and columns.
        Keys – Uses primary keys and foreign keys to link tables.
        Data Integrity – Ensures accuracy and consistency.
        ACID Properties – Maintains reliable transactions (Atomicity, Consistency, Isolation, Durability).
        SQL Support – Uses SQL to manage and query data.
        ```
    
🟢5. What are the types of database languages?
```
    DDL (Data Definition Language)
        – Used to create and modify database structure.
        – Example: CREATE, ALTER, DROP

    DML (Data Manipulation Language)
        – Used to insert, update, delete, or retrieve data.
        – Example: SELECT, INSERT, UPDATE, DELETE

    DCL (Data Control Language)
        – Used to control access and permissions.
        – Example: GRANT, REVOKE

    TCL (Transaction Control Language)
        – Used to manage transactions in the database.
        – Example: COMMIT, ROLLBACK, SAVEPOINT
        ```

🟢6. Explain ACID properties.
```
    ACID Properties
    ACID ensures that database transactions are reliable and safe.

    🔹 A – Atomicity
        A transaction is all or nothing.
        🧠 If one part fails, the whole transaction is rolled back.

    🔹 C – Consistency
        Keeps the database in a valid state.
        🧠 Data always follows rules and constraints.

    🔹 I – Isolation
        Transactions run independently of each other.
        🧠 One transaction doesn’t affect another running at the same time.

    🔹 D – Durability
        Once a transaction is committed, the data is saved permanently, even after a crash.
        🧠 Changes won’t be lost.
        ```

🟢7. Difference between vertical and horizontal scaling.
```
    
         Vertical Scaling	                      Horizontal Scaling
    Add resources to one server	          Add more servers to the system
    Easier to implement	                  More scalable and flexible
    Has a limit	                          Can scale almost infinitely
    ```

🟢8. What is sharding in DBMS?
```
     Sharding is a method of splitting a large database into smaller parts, called shards,
     so that each shard can be stored on a different server.

    🧠 Think: Breaking one big book into smaller chapters and storing them in different places to make reading faster.
    ```

🟢9. What are Keys in DBMS?
```
     Keys are special fields in a table used to identify rows and create relationships between tables.

    ✅ Common Types of Keys:
        Primary Key – Uniquely identifies each record in a table.
        Foreign Key – Connects one table to another.
        Candidate Key – All possible unique keys; one becomes the primary key.
        Composite Key – A key made from two or more columns.
        Unique Key – Ensures all values in a column are different.
        ```

🟢10. Types of Relationships in DBMS.
```
       One-to-One (1:1)
       One-to-Many (1:M)
       Many-to-One (M:1)
       Many-to-Many (M:N)
       ```

🟢11. What is Data Abstraction in DBMS? Mention its three levels.
```
      Data Abstraction means hiding the complex details of how data is stored and 
      showing only the necessary part to the user.

        Physical Level – Describes how data is actually stored (files, memory, etc.).
        Logical Level – Describes what data is stored and the relationships (tables, columns).
        View Level – Shows only part of the data to the user (like a custom report).
        ```

🟢12. What is Indexing in DBMS? Why Use Indexing?
```
      Indexing is a technique used to speed up data retrieval in a database.

        Makes searching faster
        Improves query performance
        ```
 
🟢13. What is DDL (Data Definition Language)?
```
     DDL is a set of SQL commands used to define or change the structure of database
     objects like tables, schemas, or indexes.

    🧠 Think: DDL is used to create and organize your database layout.

    ✅ Common DDL Commands:
        CREATE – Makes a new table or database
        ALTER – Changes an existing table
        DROP – Deletes a table or database
        TRUNCATE – Removes all records from a table
        ```

🟢14. What is DML (Data Manipulation Language)?
```
     DML is a set of SQL commands used to insert, update, delete, and retrieve data from a database.

    ✅ Common DML Commands:
        SELECT – Retrieve data
        INSERT – Add new data
        UPDATE – Modify existing data
        DELETE – Remove data
        ```



🟢15. What is Normalization? Mention its types.
```
      It a technique to reduce or remove redundancy from table .


      ✅ Types (Forms) of Normalization:
            1NF: Removes repeating groups; each cell has a single value.
            2NF: Removes partial dependency; applies only to tables with composite keys.
            3NF: Removes transitive dependency; non-key columns depend only on the primary key.
            BCNF: A stronger version of 3NF; every determinant is a candidate key.
            ```



🟢16. What is Denormalization?
```
      Denormalization is the process of adding redundant data to a database to improve read
      performance by reducing the number of joins. It is the opposite of normalization.
      ```

🟢17. What is Functional Dependency?
```
        Functional dependency is a relationship where one column's value depends on another column.
        If A → B, it means the value of A uniquely determines the value of B.
        ```

🟢18. What is an E-R Model (Entity RelationShip Model).
```
    Anythinks which have some physical existance.
    ```

🟢19. What is Conflict Serializability in DBMS?
```
        Conflict serializability is a type of scheduling where a non-serial schedule can be 
        converted to a serial schedule by swapping non-conflicting operations.
      copy (83,84,85,86)
      ```

🟢20. Explain Normal Forms in DBMS.
```
      Normal forms are rules used to organize database tables to reduce data 
      redundancy and improve data integrity.

      The main normal forms are:
        1NF: Removes repeating groups; each cell has a single value.
        2NF: Removes partial dependency; applies only to tables with composite keys.
        3NF: Removes transitive dependency; non-key columns depend only on the primary key.
        BCNF: A stronger version of 3NF; every determinant is a candidate key. 
        ```

🟢21. What is CCP (Concurrency Control Protocols)?
```
      Concurrency Control Protocols are rules used in DBMS to manage the simultaneous execution 
      of transactions without conflicts, ensuring data consistency and isolation.
      ```

🟢22. Define Entity, Entity Type, Weak Entity Set, and Entity Set.
```
     
    Entity:-
    Anythinks which have some physical existance.
    👉 Example: A student, car, or employee.

    Entity Type:- A collection of entities with the same attributes.
    👉 Example: "Student" is an entity type with attributes like Roll No, Name, etc.

    Entity Set: A group of similar entities in a database.
    👉 Example: All students in a college form a student entity set.

    Weak Entity Set: An entity set that does not have a primary key and depends on a strong entity for identification.
    👉 Example: "Dependent" of an employee.
    ```
      
🟢23. What are SQL Commands? Mention types of them.
```
      SQL commands are instructions used to communicate with a database to perform tasks l
      ike retrieving, updating, or managing data.

    Types of SQL Commands:
        DDL (Data Definition Language): Create, alter, drop tables (e.g., CREATE, ALTER, DROP)
        DML (Data Manipulation Language): Insert, update, delete data (e.g., INSERT, UPDATE, DELETE)
        DCL (Data Control Language): Manage permissions (e.g., GRANT, REVOKE)
        TCL (Transaction Control Language): Manage transactions (e.g., COMMIT, ROLLBACK)
        ```

🟢24. What are Nested Queries in SQL?
```
      Nested queries are queries placed inside another query. The inner query runs first, 
      and its result is used by the outer query. Also called subqueries.
      ```

🟢25. What is a JOIN in SQL? Explain its types.
```
      A JOIN is used to combine rows from two or more tables based on a related column.
      
    Types of JOINs:
        INNER JOIN: Returns only matching rows from both tables.
        LEFT JOIN (or LEFT OUTER JOIN): Returns all rows from the left table and matching rows from the right table.
        RIGHT JOIN (or RIGHT OUTER JOIN): Returns all rows from the right table and matching rows from the left table.
        FULL JOIN (or FULL OUTER JOIN): Returns all rows when there is a match in either table.
        ```

🟢26. What are Inner and Outer Joins?
```

    Inner Join: Returns only the rows that have matching values in both tables.

    Outer Join: Returns matching rows plus rows with no match from one or both tables.

    Types of Outer Join:
        Left Outer Join: All rows from left table + matched rows from right.
        Right Outer Join: All rows from right table + matched rows from left.
        Full Outer Join: All rows from both tables, matched or not.
        ```

🟢27. Practice SQL queries from LeetCode.
```

```
🟢28. Difference between 2-tier and 3-tier architecture.
```
      copy(4)
      ```

🟢29. Difference between TRUNCATE and DELETE commands.
```

                DELETE	                                                           TRUNCATE
        Deletes rows one by one                        	              Removes all rows by deallocating data pages
        Can use WHERE clause to delete specific rows	              Cannot use WHERE clause; removes all rows
        Logs each row deletion	                                      Performs minimal logging
        Slower for large tables                                       Faster for large tables
        Activates triggers	                                          Does NOT activate triggers
        Can be rolled back if used within a transaction	              Usually can be rolled back, but some DBs don’t support rollback
        Does not reset identity (auto-increment)	                  Resets identity (auto-increment values)
        ```

🟢30. Difference between Intension and Extension in a Database.
🟢31. Difference between Share Lock and Exclusive Lock, and define Lock.



🟢32 What is Schema 
```
   Shema is a blueprint or structure that define how the data is organised 
   and related within a database.
   ``` 


🟢33 Three schema Architecture / Three Level of Abstruction 
```
    
    External Schema     or   view level
                                                    Logical data independency 
    Conceptual Schema   or   logical lebel 
                                                    Physical data independency 
    Physical Schema     or   Internal Level
    ```

🟢34 Data Independence ?
```
   capacity to change  Schema at one level of a database system without having to 
   change the schema at the next high level.
   ```

🟢35 Logical Data Independency
```
   Ability to modify the conceptual schema without changing the external schema . 
   ```  

🟢36 Physical Data Independency
```
   Ability to modify the internal schema without changing the conceptual schema .
   ```

🟢37 Integrity Constraints 
```
    Integrity constrain are rules define in data base to maintain data accuracy , consistency and reliability.

    it is used to maintain quality information.
    ```

🟢38 Types of Integrity constraints
```
        Domain constraints
        Entity Integrity constraints
        Referencial Integrity constraints
        Key constraints
        ```

🟢39  Defination of candidate Key .
```
    A candidate key is a column (or a set of columns) in a table that can uniquely identify 
    each row and does not allow null values.

    Candidate Key = Unique + Not Null

    A table can have multiple candidate keys.
    ```
      
🟢40  Definition of Primary Key:
```
    A primary key is a column (or a set of columns) in a table that uniquely identifies
    each row and does not allow null values. 

    Primary Key = Unique + Not Null

    A primary key is chosen from the set of candidate keys.
    A table can have only one primary key.
    It ensures that each record in the table is uniquely identifiable.
    ```

🟢41  Definition of Foreign Key .
```
    It is an attribute or set of attributes that references to primary key of
    same table or another table. 

    Foreign Key = Reference to Primary Key of another table

    It is used to maintain referential integrity between related tables.
    A foreign key can have duplicate values and can contain null values, unless explicitly restricted.
    A table can have multiple foreign keys.
    ```

🟢42 Types of attribute in Er model
```
        Sigles and Multivalues attribute
        Simple vs Composite attribute
        Stored vs Derive attribute 
        key vs Non-key attribute
        Required vs Optimal Attribute
        Complex attribute 
        ```

🟢43 Degree of Relationship
```
        One to one 
        one to many 
        many to one 
        many to many 
        ```


