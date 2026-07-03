# Day 08 - Login Page Development and User Authentication

**Date:** 1 July 2026

## Overview

Today was the eighth day of my Web Development Training. After successfully completing the Employee Registration Page, I started working on the Login Module of the Employee Management System.

The main objective of today's session was to create a professional login page and establish its connection with the MySQL database using PHP. I learned how to fetch user records from the database using the SQL `SELECT` statement and validate user credentials during login.

This was an important milestone in my project because the application now supports both user registration and login functionality.

---

## Topics Learned

### Login System Development

- Designing a Login Page
- User Authentication
- PHP and MySQL Integration
- SQL `SELECT` Statement
- Fetching Records from Database
- Validating User Credentials
- Processing Login Requests

### PHP Concepts

- Database Connectivity using `mysqli`
- Executing SQL Queries
- Fetching Data using `mysqli_query()`
- Retrieving Records using `mysqli_fetch_assoc()`
- Conditional Statements for Login Validation

---

## Practical Work

During today's practical session, I:

- Designed a professional Login Page.
- Connected the login page to the MySQL database.
- Used the SQL `SELECT` statement to retrieve user information.
- Compared the entered email and password with the stored database records.
- Displayed appropriate messages for successful and unsuccessful login attempts.
- Tested the login functionality using registered employee records.

---

## Employee Management System Progress

Today I completed the login module for my Employee Management System.

### Features Implemented

- Professional Login Interface
- Database Connectivity using PHP
- User Authentication
- Fetching Employee Details from Database
- Login Validation
- Error Handling for Invalid Credentials

### SQL Query Used

- `SELECT` Statement to fetch employee records from the database.

### Workflow

1. User enters Email and Password.
2. PHP receives the form data.
3. PHP connects to the MySQL database.
4. A `SELECT` query checks whether the entered credentials exist.
5. If the credentials are valid, the user is authenticated successfully.
6. Otherwise, an appropriate error message is displayed.

---

## Key Learnings

- The SQL `SELECT` statement is used to retrieve data from a database.
- PHP can communicate with MySQL to authenticate users.
- Login systems verify user credentials before granting access.
- Proper database connectivity is essential for secure authentication.
- Testing different login scenarios helps identify and fix issues.

---

## Challenges Faced

- Writing the correct SQL query for user authentication.
- Matching user input with database records.
- Handling invalid login attempts correctly.

---

## How I Overcame Them

- Practiced writing SQL `SELECT` queries.
- Verified database connection settings.
- Tested the login system with multiple user records.
- Debugged errors by checking query results and PHP logic.

---

## Conclusion

Today's session was a significant step in developing the Employee Management System. I successfully created a login page and connected it to the MySQL database using PHP. By implementing the SQL `SELECT` statement, I was able to fetch employee records and authenticate users based on their login credentials. The project now includes both user registration and login functionalities, making it more complete and closer to a real-world web application.

---

## Next Day Goal

- Implement Session-Based Login.
- Redirect users after successful login.
- Create a Dashboard page.
- Restrict unauthorized access to protected pages.
- Continue improving the Employee Management System.
