Project Title: Library Management System

Project Description:
I am excited to present my Library Management System, a comprehensive database designed to manage a library's book inventory, members, and borrowing activities. This project demonstrates my ability to design a relational database, write Basic SQL queries, and handle various database operations effectively. By creating and managing this system, I showcase my proficiency in database management, data manipulation, and SQL querying.

Project Schema:

Tables:

Books
- BookID (Primary Key): Unique identifier for each book.
- Title: The title of the book.
- Author: The author of the book.
- Genre: The genre of the book.
- PublishedYear: The year the book was published.
- ISBN: The International Standard Book Number.
- CopiesAvailable: The number of copies available for borrowing.

Members
- MemberID (Primary Key): Unique identifier for each library member.
- FirstName: The first name of the member.
- LastName: The last name of the member.
- DateOfBirth: The birthdate of the member.
- Email: The email address of the member.
- PhoneNumber: The contact number of the member.
- MembershipStartDate: The date the membership started.

Borrowing
- BorrowingID (Primary Key): Unique identifier for each borrowing transaction.
- BookID (Foreign Key): References the unique identifier of the borrowed book.
- MemberID (Foreign Key): References the unique identifier of the member who borrowed the book.
- BorrowDate: The date the book was borrowed.
- ReturnDate: The date the book was returned.


Step 1: Setting Up the Database

Step 2: Inserting Sample Data in all tables.

-- Inserting values in Books table
	INSERT INTO lms.books VALUES 
	(1, 'To Kill a Mockingbird', 'Harper Lee', 'Fiction', 1960, '1234567890', 5),
	(2, '1984', 'George Orwell', 'Dystopian', 1949, '1234567891', 3),
	(3, 'The Great Gatsby', 'F. Scott Fitzgerald', 'Classic', 1925, '1234567892', 4),
	(4, 'Harry Potter and the Sorcerer\'s Stone', 'J.K. Rowling', 'Fantasy', 1997, '1234567893', 7),
	(5, 'The Catcher in the Rye', 'J.D. Salinger', 'Classic', 1951, '1234567894', 6),
	(6, 'Pride and Prejudice', 'Jane Austen', 'Romance', 1813, '1234567895', 4),
	(7, 'The Hobbit', 'J.R.R. Tolkien', 'Fantasy', 1937, '1234567896', 8),
	(8, 'Fahrenheit 451', 'Ray Bradbury', 'Dystopian', 1953, '1234567897', 5),
	(9, 'Moby Dick', 'Herman Melville', 'Adventure', 1851, '1234567898', 3),
	(10, 'War and Peace', 'Leo Tolstoy', 'Historical', 1869, '1234567899', 2);


-- Inserting values in Members table
	INSERT INTO lms.members VALUES
	(1, 'John', 'Doe', '1990-01-01', 'john.doe@example.com', '123-456-7890', '2025-01-01'),
	(2, 'Jane', 'Smith', '1985-05-15', 'jane.smith@example.com', '098-765-4321', '2025-01-15'),
	(3, 'Michael', 'Johnson', '1992-09-10', 'michael.johnson@example.com', '234-567-8901', '2025-02-01'),
	(4, 'Emily', 'Brown', '1988-07-22', 'emily.brown@example.com', '345-678-9012', '2025-02-10'),
	(5, 'David', 'Williams', '1995-04-05', 'david.williams@example.com', '456-789-0123', '2025-03-01'),
	(6, 'Sarah', 'Jones', '1991-11-20', 'sarah.jones@example.com', '567-890-1234', '2025-03-15'),
	(7, 'Chris', 'Miller', '1987-03-30', 'chris.miller@example.com', '678-901-2345', '2025-04-01'),
	(8, 'Amanda', 'Davis', '1994-06-15', 'amanda.davis@example.com', '789-012-3456', '2025-04-10'),
	(9, 'Daniel', 'Garcia', '1993-08-25', 'daniel.garcia@example.com', '890-123-4567', '2025-05-01'),
	(10, 'Laura', 'Martinez', '1986-12-12', 'laura.martinez@example.com', '901-234-5678', '2025-05-15');


-- Inserting values in borrowing table
	INSERT INTO lms.borrowing VALUES
	(1, 1, 1, '2025-02-01', NULL),
	(2, 2, 2, '2025-02-05', '2025-02-12'),
	(3, 3, 3, '2025-02-10', NULL),
	(4, 4, 4, '2025-02-15', '2025-02-22'),
	(5, 5, 5, '2025-03-01', NULL),
	(6, 6, 6, '2025-03-05', '2025-03-12'),
	(7, 7, 7, '2025-03-10', NULL),
	(8, 8, 8, '2025-03-15', '2025-03-22'),
	(9, 9, 9, '2025-03-20', NULL),
	(10, 10, 10, '2025-03-25', '2025-04-01');
	
	

Step 3: Running SQL Queries
	-- Write a query to retrieve all books from the Books table.
	-- Write a query to list books borrowed by a specific member.
	-- Write a query to find books that are available for borrowing.
	-- Write a query to update the number of available copies after a book is borrowed.
	-- Write a query to delete a book record from the Books table.


By completing this project, I demonstrated my ability to design and manage a relational database, write effective SQL queries, and perform essential database operations. This project not only highlights my technical skills but also my attention to detail and ability to handle real-world data scenarios. 📚💻

If you have any questions or need further information about my project, feel free to reach out!
