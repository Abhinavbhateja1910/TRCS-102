# Day 19 - Implementing Search and Sorting Functionality

**Date:** 16 July 2026

## Overview

Today was the nineteenth day of my Web Development Training. The focus of today's session was on enhancing the **Employee List** page by implementing **Search** and **Sorting** functionalities.

I added a search bar that allows users to quickly find employee records by entering relevant information. Additionally, I implemented a sorting feature that enables users to arrange employee records based on salary in **Ascending (Low to High)** or **Descending (High to Low)** order.

These features significantly improved the usability and functionality of the Employee Management System by making employee records easier to search and organize.

---

## Topics Learned

### PHP and MySQL

- Searching Records in Database
- SQL `SELECT` Statement with `WHERE` Clause
- Using `LIKE` Operator
- Sorting Records using `ORDER BY`
- Ascending (`ASC`) and Descending (`DESC`) Sorting
- Dynamic SQL Queries
- Handling User Input in PHP

### Web Development Concepts

- Search Bar Implementation
- Sorting Dropdown
- Dynamic Data Filtering
- User-Friendly Interface
- Improving Data Accessibility

---

## Practical Work

During today's practical session, I:

- Added a search bar to the Employee List page.
- Implemented search functionality using PHP and MySQL.
- Used the SQL `LIKE` operator to search employee records.
- Added a sorting dropdown with multiple options.
- Implemented salary sorting in both ascending and descending order.
- Displayed the filtered and sorted results dynamically.
- Tested the search and sorting features with different employee records.

---

## Employee Management System Progress

Today I improved the Employee List page by making it easier to search and organize employee data.

### Features Implemented

- Employee Search Bar
- Dynamic Search Functionality
- Salary Sorting (Low to High)
- Salary Sorting (High to Low)
- Filtered Employee Records
- Improved User Experience

### Search Functionality

Users can search employee records using:

- Employee Name
- Email Address
- Mobile Number
- Other relevant employee details stored in the database

### Sorting Options

- Salary: Low to High
- Salary: High to Low

---

## Workflow

### Search Operation

1. User enters a keyword in the search bar.
2. PHP receives the search input.
3. A SQL `SELECT` query with the `LIKE` operator is executed.
4. Matching employee records are retrieved.
5. The filtered results are displayed dynamically.

### Sorting Operation

1. User selects a sorting option.
2. PHP receives the selected option.
3. A SQL `ORDER BY` query is executed.
4. Employee records are sorted based on salary.
5. The sorted list is displayed on the Employee List page.

---

## Key Learnings

- The SQL `LIKE` operator is useful for searching records based on user input.
- The `ORDER BY` clause sorts database records efficiently.
- Search and sorting features improve the usability of web applications.
- Dynamic SQL queries allow data to be displayed according to user preferences.
- User-friendly features make applications more interactive and efficient.

---

## Challenges Faced

- Writing SQL queries for dynamic searching.
- Implementing multiple sorting options.
- Ensuring that search and sorting worked together correctly.
- Testing different search keywords and sorting combinations.

---

## How I Overcame Them

- Practiced SQL queries using the `LIKE` and `ORDER BY` clauses.
- Tested the application with different employee records.
- Debugged query logic to ensure accurate search results.
- Verified that sorting displayed records in the correct order.

---

## Conclusion

Today's session focused on enhancing the Employee Management System by implementing search and sorting functionality. I successfully added a search bar to filter employee records and a sorting option to arrange employees based on salary in ascending or descending order. These improvements make the Employee List page more efficient, user-friendly, and closer to a real-world employee management application.

---

## Next Day Goal

- Improve the overall user interface of the Employee Management System.
- Add pagination or additional filtering options.
- Optimize database queries for better performance.
- Continue enhancing the project with new features.
