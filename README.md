# Database
#  Library Management System

## Project Description
The *Library Management System* is a MySQL-based project that allows the management of books, authors, members, borrowing transactions, and librarians in a library. This system models real-world interactions and relationships within a library using a relational database.

##  Features
- Store and manage *book* details
- Track *authors* and their books
- Register *members* and their join dates
- Manage *borrowing records* (who borrowed which book and when)
- Maintain *librarian* information

##  Database Structure

### Tables:
- Authors – holds data about book authors
- Books – stores book titles, genres, and copies
- Members – keeps records of library members
- Librarians – stores librarian data
- Borrow – logs borrowing and return activity

### Relationships:
- One Author ➝ Many Books
- One Member ➝ Many Borrowings
- One Book ➝ Many Borrowings
- Borrow table resolves many-to-many between Members and Books

##  How to Run / Setup

1. Clone this repository:
   git clone:
