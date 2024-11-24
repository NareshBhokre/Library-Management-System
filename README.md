# Library-Management-System Task-1
# Problem Statement:
Design and Implement a Relational Database for a Library Management System

Create database LibraryManagementSystem;

CREATE TABLE Books (
    book_id INT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    isbn VARCHAR(13) UNIQUE NOT NULL,
    publish_year INT,
    category_id INT
    );
    
    INSERT INTO Books (book_id, title, isbn, publish_year, category_id)
    VALUES (1,'The Great Gatsby', '9780743273565', 1925, 5);

SELECT * FROM Books



