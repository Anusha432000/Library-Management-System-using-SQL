# Library-Management-System-using-SQL
An intermediate-level SQL project demonstrating the development of a Library Management System. This includes end-to-end database design, implementation of CRUD operations, advanced querying, use of stored procedures, and analytics.
🚀 Project Overview
Project Title: Library Management System
This project simulates a fully functional library management system, built purely using SQL. It includes setting up relational database tables, performing CRUD operations, executing advanced queries, generating reports, and implementing stored procedures for issuing and returning books.

🎯 Objectives
Set up a normalized library database schema

Implement CRUD operations on books, members, employees, etc.

Use CTAS (Create Table As Select) to generate analytical summary tables

Write advanced SQL queries to retrieve insights, detect overdue books, and calculate fines

Develop and test stored procedures to automate operations like book issuance and returns

🧱 Project Structure
1. 📂 Database Setup
Database Created: library_db

Tables:

branch

employees

members

books

issued_status

return_status

ERD: Models branches, staff, members, book inventory, issuance, and returns

2. ✍️ CRUD Operations
Create: Inserted new books, members, and employees

Read: Queried books by category, availability, and issue status

Update: Updated member addresses and book statuses

Delete: Removed obsolete issued records

3. 🧮 Advanced SQL Queries
Members with multiple book issues

Rental income by book category

Overdue books and fines

Employees issuing the most books

Branch-wise performance reports

Active members in the last 2 months

4. ⚙️ Stored Procedures
issue_book: Issues a book and updates inventory status

add_return_records: Handles book returns and updates availability

5. 📊 Reports & Analysis
Branch Reports: Revenue, book issues/returns by branch

Overdue Books: With fine calculation

Employee Performance: Top employees by issues processed

Active Members: Based on recent activity

Damaged Books Tracking: Identify frequent issuers of damaged books

📌 Key Features & Highlights
Feature	Description
🔧 Normalized DB Design	Realistic schema for library entities
📊 Analytical Queries	Rental insights, overdue tracking, fines, and revenue
🔁 CTAS Usage	Efficiently created summary tables using CREATE TABLE AS SELECT
🧠 Stored Procedures	Automated issuance and returns with validations
📈 Reports	Performance metrics at member, branch, and employee levels

✅ Sample Tasks Covered
📥 Insert new book records

✏️ Update member and book information

❌ Delete issued or returned entries

📚 Analyze overdue books and calculate fines

📊 Generate branch and employee performance reports

🧑‍💼 Identify active members and frequent issuers

📊 Sample Outputs
🗓️ Overdue Books Report with Days Overdue & Fine

🧍‍♂️ Active Members Table (last 2 months)

🏢 Branch Performance Report

👩‍💼 Top Performing Employees

📕 List of Expensive or Frequently Damaged Books
🏁 Conclusion
This project showcases how SQL can be leveraged to build and manage a complete Library Management System. It demonstrates skills in relational modeling, CRUD operations, analytics, automation with stored procedures, and performance reporting — essential for real-world database and data analysis roles.
🧑‍💻 Author
Anusha P

