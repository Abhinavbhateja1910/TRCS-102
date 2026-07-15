# Day 18 - Employee Information Page and Responsive Design

**Date:** 15 July 2026

## Overview

Today was the eighteenth day of my Web Development Training. The focus of today's session was on enhancing the Employee Management System by creating a dedicated **Employee Information** page.

I developed a new page named **info.php**, which displays the complete details of a selected employee. To access this page, I added an **Eye (View)** icon to the Employee List page. When the icon is clicked, the employee's unique ID is passed to **info.php**, where PHP retrieves the corresponding record from the MySQL database using a SQL `SELECT` query. The employee's complete information is then displayed in a well-organized format.

In addition, I made the **info.php** page fully responsive so that it works smoothly on desktops, tablets, and mobile devices.

---

## Topics Learned

### PHP and MySQL

- Fetching a Single Record from Database
- Passing ID through URL Parameters
- SQL `SELECT` Statement with `WHERE` Clause
- Dynamic Data Retrieval
- Displaying Employee Information

### Responsive Web Design

- Responsive Page Layout
- CSS Media Queries
- Mobile-Friendly Design
- Flexible Content Layout
- Responsive Typography
- Responsive Information Cards

---

## Practical Work

During today's practical session, I:

- Created the **info.php** page.
- Added an **Eye (View)** icon to the Employee List page.
- Passed the selected employee's ID to **info.php**.
- Connected the page to the MySQL database.
- Retrieved the employee's information using the SQL `SELECT` statement.
- Displayed all employee details dynamically.
- Designed the page with a clean and professional layout.
- Made the page responsive using CSS media queries.
- Tested the page on desktop, tablet, and mobile screen sizes.

---

## Employee Management System Progress

Today I added a new feature to view complete employee information.

### Features Implemented

- Employee Information Page (`info.php`)
- Eye (View) Icon in Employee List
- Dynamic Retrieval of Employee Details
- Display of Complete Employee Information
- Responsive User Interface
- Mobile-Friendly Layout

### Employee Details Displayed

- Employee ID
- Employee Name
- Email Address
- Mobile Number
- Salary
- Date of Registration

---

## Workflow

1. User opens the **Employee List** page.
2. User clicks the **Eye (View)** icon for a specific employee.
3. The employee's unique ID is passed to **info.php**.
4. PHP connects to the MySQL database.
5. A SQL `SELECT` query with a `WHERE` clause retrieves the matching employee record.
6. The employee's complete information is displayed on the page.
7. The page adjusts automatically for different screen sizes using responsive design.

---

## Key Learnings

- The SQL `WHERE` clause is used to retrieve a specific record from the database.
- Passing an employee ID through the URL helps identify the selected record.
- Dynamic pages can display personalized information based on user actions.
- Responsive web design ensures a consistent user experience across all devices.
- Combining PHP, MySQL, and CSS creates interactive and user-friendly web applications.

---

## Challenges Faced

- Passing the correct employee ID to the information page.
- Retrieving only the selected employee's record.
- Designing a responsive layout without affecting the desktop view.

---

## How I Overcame Them

- Used the employee's unique ID to identify the correct record.
- Verified the SQL `SELECT` query with the `WHERE` condition.
- Applied CSS media queries and tested the layout on different screen sizes.
- Repeatedly tested the feature with multiple employee records to ensure accuracy.

---

## Conclusion

Today's session added another useful feature to my Employee Management System. I successfully created the **info.php** page, which displays the complete information of a selected employee when the Eye (View) icon is clicked. I also made the page fully responsive, ensuring that it provides a seamless experience on desktops, tablets, and mobile devices. This enhancement improved both the functionality and usability of my project.

---

## Next Day Goal

- Add search and sorting functionality to the Employee List page.
- Improve the overall user interface.
- Enhance project performance and code optimization.
- Continue learning advanced PHP and MySQL concepts.
