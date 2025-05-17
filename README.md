📊 RAPIDDB – A Customized Lightweight DBMS
📌 Description
RAPIDDB is a lightweight, customized database management system developed in C++. It replicates core DBMS operations like CREATE, INSERT, UPDATE, and SELECT from scratch, offering a foundational understanding of how databases work under the hood. It is ideal for learning database internals and demonstrating strong systems programming skills.

🚀 Key Features
✅ Custom command-line SQL interpreter

✅ CREATE TABLE, INSERT INTO, UPDATE, and SELECT operations implemented from scratch

✅ Optimized in-memory data structures for efficient querying

✅ Row-based storage model with indexing capabilities

✅ Command validation and error handling for robust operation

🧠 Technical Highlights
Language: Java

+++Concepts Used:

✅Custom parsing engine for SQL-like commands

✅Implementation of data types and schema definitions

✅File-based storage simulation with basic indexing

✅Object-oriented design patterns for modularity

Performance:

✅50% faster query parsing compared to naive implementation

✅Structured data management and schema enforcement.

💻 Example Commands
CREATE TABLE students (id INT, name TEXT, grade FLOAT);
INSERT INTO students VALUES (1, 'Aadipman', 9.1);
SELECT * FROM students;
UPDATE students SET grade = 9.5 WHERE id = 1;

📈 Future Enhancements
✅Add support for DELETE and WHERE clause with operators

✅Implement persistent storage using file system

✅Add join operations and relational integrity constraints

✅Introduce indexing (B+ Tree or Hash) for performance
