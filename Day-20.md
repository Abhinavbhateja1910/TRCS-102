# Day 20 - Task Management Module Implementation

**Date:** 17 July 2026

## Overview

Today was the twentieth day of my Web Development Training. The focus of today's session was on extending the Employee Management System by introducing a **Task Management Module**.

I developed two new pages: **createtask.php** and **tasks.php**. The **createtask.php** page allows administrators to create and assign tasks to employees by providing task details such as title, description, assigned employee, priority, due date, and status. The **tasks.php** page displays all the assigned tasks in a structured table and includes search and sorting functionalities to manage tasks efficiently.

This enhancement made the Employee Management System more practical by enabling task allocation and tracking.

---

## Topics Learned

### PHP and MySQL

- Task Management System
- Database Operations using PHP
- SQL `INSERT` Statement
- SQL `SELECT` Statement
- Dynamic Data Retrieval
- Form Handling in PHP
- Managing Relationships Between Employees and Tasks

### Web Development Concepts

- Task Creation Form
- Dynamic Task Listing
- Search Functionality
- Sorting Records
- Data Organization
- User-Friendly Interface

---

## Practical Work

During today's practical session, I:

- Created the **createtask.php** page.
- Designed a task creation form.
- Connected the form to the MySQL database using PHP.
- Stored task details in the database.
- Created the **tasks.php** page.
- Displayed all assigned tasks in a dynamic table.
- Implemented search functionality for tasks.
- Added sorting options to organize task records.
- Tested task creation and retrieval with multiple employee records.

---

## Employee Management System Progress

Today I successfully integrated a complete **Task Management Module** into my Employee Management System.

### Features Implemented

#### Create Task Page (`createtask.php`)

The task creation form includes the following fields:

- Task Title
- Task Description
- Allotted To (Employee)
- Priority
- Due Date
- Task Status

#### Tasks Page (`tasks.php`)

- Display All Assigned Tasks
- Dynamic Task List
- Search Bar
- Sorting Options
- Professional Table Layout

---

## Task Details Displayed

- Task ID
- Task Title
- Description
- Assigned Employee
- Priority
- Due Date
- Status

---

## Workflow

### Task Creation

1. Open the **Create Task** page.
2. Enter the task title and description.
3. Select the employee to whom the task will be assigned.
4. Choose the priority level.
5. Set the due date.
6. Select the current task status.
7. Submit the form.
8. PHP stores the task information in the MySQL database.

### Task Management

1. Open the **Tasks** page.
2. PHP retrieves all task records from the database.
3. All tasks are displayed in a dynamic table.
4. Users can search for specific tasks using the search bar.
5. Users can sort tasks based on the available sorting options.
6. The filtered or sorted task list is displayed dynamically.

---

## Key Learnings

- A task management module improves the functionality of an Employee Management System.
- PHP forms can be used to insert task records into a database.
- SQL `INSERT` and `SELECT` statements are essential for managing task information.
- Search and sorting functionalities improve data accessibility and user experience.
- Organizing tasks helps monitor employee responsibilities and project progress.

---

## Challenges Faced

- Designing the task creation form with multiple input fields.
- Linking tasks to the correct employee.
- Displaying task information dynamically.
- Implementing search and sorting without affecting data accuracy.

---

## How I Overcame Them

- Carefully designed the database structure for task management.
- Used PHP and MySQL to connect task records with employee information.
- Tested task creation using multiple employee records.
- Verified search and sorting functionality with different datasets.
- Debugged SQL queries to ensure accurate task retrieval.

---

## Conclusion

Today's session was a major milestone in the development of my Employee Management System. I successfully implemented a **Task Management Module** by creating **createtask.php** and **tasks.php**. The system can now assign tasks to employees, store task details in the database, display all assigned tasks, and provide search and sorting functionality. These features make the project more practical, organized, and closer to a real-world employee management application.

---

## Next Day Goal

- Add task editing and deletion functionality.
- Display task details on individual pages.
- Improve the user interface of the Task Management Module.
- Continue enhancing the Employee Management System with advanced features.
