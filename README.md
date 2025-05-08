# Library Management System Database

## Project Description
This is a complete MySQL database for a Library Management System. It tracks books, members, loans, reservations, fines, and other library operations. The database is designed with proper relationships, constraints, and indexes for optimal performance.

## Features
- Member management
- Book catalog with authors and publishers
- Loan tracking with due dates
- Fine calculation for overdue books
- Reservation system
- Staff management
- Audit logging

## Database Schema
The database consists of the following main tables:
- `members` - Library members information
- `books` - Book details
- `authors` - Author information
- `publishers` - Publisher details
- `loans` - Book loan records
- `fines` - Fine records for overdue books
- `reservations` - Book reservation records
- `staff` - Library staff information

## Entity Relationship Diagram
![Library ERD Diagram](/images/erd.JPG)

## Setup Instructions
1. Make sure you have MySQL installed
2. Run the `library_db.sql` script to create the database and all tables
   ```bash
   mysql -u username -p < library_db.sql