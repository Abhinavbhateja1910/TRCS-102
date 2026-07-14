# Day 17 - Implementing Update and Delete Operations

**Date:** 13 July 2026

## Overview

Today was the seventeenth day of my Web Development Training. The focus of today's session was on implementing the **Update** and **Delete** functionalities in my Employee Management System.

To achieve this, I enhanced the **employee.php** page by adding **Edit** and **Delete** options for each employee record. I created two new files, **edit.php** and **delete.php**, to perform the respective database operations. These features completed the basic CRUD (Create, Read, Update, Delete) functionality of my project.

---

## Topics Learned

### PHP and MySQL

- CRUD Operations
- SQL `UPDATE` Statement
- SQL `DELETE` Statement
- Passing Data through URL Parameters
- Retrieving Records using PHP
- Database Record Management
- PHP Form Handling

### Web Development Concepts

- Dynamic Action Buttons
- Edit and Delete Operations
- Data Modification
- Record Deletion
- User Interaction with Database

---

## Practical Work

During today's practical session, I:

- Added **Edit** and **Delete** buttons for every employee record.
- Created **edit.php** to update employee details.
- Created **delete.php** to remove employee records.
- Connected both pages to the MySQL database using PHP.
- Used the SQL `UPDATE` statement to modify employee information.
- Used the SQL `DELETE` statement to delete employee records.
- Tested the update and delete operations with multiple records.
- Verified that the Employee List page displayed the latest database changes automatically.

---

## Employee Management System Progress

Today I completed the remaining CRUD operations for my Employee Management System.

### Features Implemented

- Edit Employee Details
- Update Employee Information
- Delete Employee Records
- Dynamic Action Buttons
- Database Record Management
- Automatic Table Refresh After Changes

### Files Created

- **employee.php** – Displays all employee records.
- **edit.php** – Updates employee information.
- **delete.php** – Deletes employee records.

### CRUD Operations Completed

| Operation | Status |
|-----------|--------|
| Create (Registration) | ✅ Completed |
| Read (Employee List) | ✅ Completed |
| Update (Edit Employee) | ✅ Completed |
| Delete (Delete Employee) | ✅ Completed |

---

## Workflow

### Update Operation

1. Click the **Edit** button beside an employee record.
2. The employee details are loaded into **edit.php**.
3. Modify the required information.
4. Submit the form.
5. PHP executes the SQL `UPDATE` query.
6. The updated information is displayed on the Employee List page.

### Delete Operation

1. Click the **Delete** button beside an employee record.
2. PHP identifies the selected employee.
3. The SQL `DELETE` query is executed.
4. The employee record is removed from the database.
5. The Employee List page is refreshed to display the updated records.

---

## Key Learnings

- The SQL `UPDATE` statement is used to modify existing records.
- The SQL `DELETE` statement removes records from a database.
- CRUD operations are the foundation of database-driven applications.
- Dynamic action buttons improve usability and make data management easier.
- Testing every operation ensures data consistency and application reliability.

---

## Challenges Faced

- Passing the correct employee ID to the Edit and Delete pages.
- Updating the selected employee record without affecting other records.
- Ensuring that deleted records were removed correctly from the database.

---

## How I Overcame Them

- Used the employee ID as a unique identifier for each operation.
- Verified SQL queries before executing them.
- Tested the update and delete functionalities with multiple employee records.
- Carefully checked the database after each operation to confirm the changes.

---

## Conclusion

Today's session marked the completion of the core CRUD functionality of my Employee Management System. By implementing the **Update** and **Delete** operations through **edit.php** and **delete.php**, I made the application more interactive and functional. The system can now create, view, update, and delete employee records, making it a complete and practical database-driven web application.

---

## Next Day Goal

- Improve the overall user interface of the Employee Management System.
- Add confirmation messages and validations.
- Enhance security and optimize the project.
- Continue learning advanced PHP and MySQL concepts.
