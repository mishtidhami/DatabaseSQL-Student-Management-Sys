# Student Management System Database

This repository contains the SQL database for a **Student Management System**, designed to efficiently manage student, teacher, and administrative records. The database is structured to handle attendance, exams, invoices, class schedules, and more.

## Database Overview

- **Database Name**: `student_management_data`
- **Tables**:
  - `student`: Stores student details (name, birthday, contact, class, etc.).
  - `teacher`: Stores teacher details and assigned subjects.
  - `class`: Contains information about academic classes.
  - `attendance`: Records student attendance.
  - `exam`: Stores exam details.
  - `mark`: Stores student marks for exams.
  - `invoice`: Manages student fee transactions.
  - `message`: Handles communication between students, teachers, and admins.

## How to Use

1. Clone this repository:
   ```sh
   git clone https://github.com/mishti_dhami/DatabaseSQL-Student-Management-Sys.git
   ```
2. Import the SQL file into MySQL:
   ```sh
   mysql -u root -p student_management_data < student_management_data.sql
   ```
3. Use SQL queries to interact with the database.



## License

This project is open-source and can be modified as needed.
