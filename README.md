# Library-Management-System Task-1
# Problem Statement:
Design and Implement a Relational Database for a Library Management System

Create database LibraryManagementSystem;

1. CREATE TABLE Books (
    book_id INT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    isbn VARCHAR(13) UNIQUE NOT NULL,
    publish_year INT,
    category_id INT
    );
    
    INSERT INTO Books (book_id, title, isbn, publish_year, category_id)
    VALUES (1,'The Great Gatsby', '9780743273565', 1925, 5);

SELECT * FROM Books

2. CREATE TABLE Authors (
    author_id INT PRIMARY KEY,
    first_name VARCHAR(100) NOT NULL,
    last_name VARCHAR(100) NOT NULL
);

INSERT INTO Authors (author_id, first_name, last_name)
VALUES (1, 'Harry', 'Potter')

SELECT * FROM Authors

3. CREATE TABLE BookAuthors (
    book_id INT,
    author_id INT
    );
    
INSERT INTO BookAuthors (book_id, author_id)
VALUES (1,1)

SELECT * FROM BookAuthors

4. 



