The Library Management System project involves creating a database to manage and track all aspects of a library's operations, including books, employees, customers, and book transactions. Here's a summary of the data and the tasks covered in the project:

Database and Tables:
Branch Table: Stores information about library branches, including branch number, manager ID, address, and contact number.
Employee Table: Contains details about employees, such as employee ID, name, position, salary, and the branch they work in. The Branch_no is a foreign key referencing the Branch table.
Books Table: Manages information about books in the library, including ISBN, title, category, rental price, availability status, author, and publisher.
Customer Table: Records customer details, including customer ID, name, address, and registration date.
IssueStatus Table: Tracks which customer has issued which book and when. It includes the issue ID, customer ID (foreign key), book ISBN (foreign key), and the issue date.
ReturnStatus Table: Keeps track of the return details of books, including return ID, customer ID (foreign key), book ISBN (foreign key), and the return date.
