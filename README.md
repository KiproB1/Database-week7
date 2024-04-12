# Database-week7
Primary and foreign key
A primary key and a foreign key are both important concepts in relational database management systems (RDBMS) like MySQL, PostgreSQL, Oracle, and SQL Server. They are used to establish relationships between tables and enforce data integrity.

1. Primary Key:
   - Definition: A primary key is a unique identifier for each record (row) in a table. It uniquely identifies each record in the table and ensures that no two records have the same key.
   - Characteristics:
     - Uniqueness: Each value in the primary key column must be unique within the table.
     - Non-null: The primary key column cannot contain NULL values.
     - Single-column or Composite: A primary key can consist of one or multiple columns. In the case of a composite primary key, the combination of values from multiple columns must be unique.
   - Purpose:
     - Uniquely identify records: The primary key ensures that each record in the table is uniquely identifiable.
     - Ensure data integrity: By enforcing uniqueness and non-null constraints, the primary key helps maintain data integrity within the table.
   - Example: In a "Students" table, the "StudentID" column can serve as the primary key, ensuring that each student record has a unique identifier.

2. Foreign Key:
   - Definition: A foreign key is a field (or a set of fields) in one table that refers to the primary key in another table. It establishes a relationship between the two tables based on their common attributes.
   - Characteristics:
     - References: A foreign key references the primary key (or a unique key) of another table.
     - Constraint: It imposes referential integrity constraints, ensuring that the values in the foreign key column must exist in the referenced table's primary key column (or a unique key column).
   - Purpose:
     - Establish relationships: Foreign keys establish relationships between tables, representing dependencies or associations between them.
     - Maintain data consistency: By enforcing referential integrity, foreign keys ensure that relationships between tables remain consistent and valid.
   - Example: In a "Orders" table, the "CustomerID" column may serve as a foreign key referencing the "CustomerID" primary key column in a "Customers" table, indicating which customer placed each order.

In summary, a primary key uniquely identifies records within a table, while a foreign key establishes relationships between tables by referencing the primary key of another table. Together, they play a crucial role in maintaining data integrity and ensuring the consistency of relational databases.
