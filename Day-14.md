# Day 14 - Project Refactoring and Code Organization

**Date:** 9 July 2026

## Overview

Today was the fourteenth day of my Web Development Training. The focus of today's session was on improving the organization and maintainability of my Employee Management System project.

Instead of maintaining separate CSS and JavaScript files for different pages, I refactored the project by creating a single **style.css** file for all styling and a single **custom.js** file for all JavaScript functionality. This made the project cleaner, easier to manage, and more aligned with professional web development practices.

---

## Topics Learned

### Project Refactoring

- Code Refactoring
- File Organization
- Reusable CSS
- Reusable JavaScript
- Project Maintainability
- Code Optimization
- Separation of Concerns

### Best Practices

- Writing Common CSS for Multiple Pages
- Centralized JavaScript Management
- Reducing Code Duplication
- Improving Project Scalability
- Maintaining a Clean Folder Structure

---

## Practical Work

During today's practical session, I:

- Removed separate CSS files for the Registration and Login pages.
- Created a single **style.css** file to manage the styling of all pages.
- Combined the common styles from different pages into one stylesheet.
- Removed separate JavaScript files for the Registration and Login pages.
- Created a single **custom.js** file to handle all client-side functionality.
- Updated file references in all project pages.
- Tested the project after refactoring to ensure all pages functioned correctly.

---

## Employee Management System Progress

Today I improved the overall project structure by making the code more organized and reusable.

### Improvements Made

- Created a common **style.css** file.
- Created a common **custom.js** file.
- Removed duplicate CSS code.
- Removed duplicate JavaScript code.
- Improved project organization.
- Simplified file management.
- Enhanced code reusability.
- Made future maintenance easier.

### Project Structure

```
Employee-Management-System/
│
├── css/
│   └── style.css
│
├── js/
│   └── custom.js
│
├── register.php
├── login.php
├── dashboard.php
└── assets/
```

---

## Key Learnings

- Refactoring improves the quality and maintainability of a project.
- A single stylesheet helps maintain a consistent design across all pages.
- A common JavaScript file reduces code duplication.
- Well-organized project files make future development easier.
- Writing reusable code is an important professional development practice.

---

## Challenges Faced

- Combining styles without affecting the existing design.
- Ensuring JavaScript functionality worked correctly after merging files.
- Updating file paths and references across the project.

---

## How I Overcame Them

- Carefully reviewed and merged common CSS rules.
- Organized JavaScript functions logically in one file.
- Updated all page references to the new files.
- Thoroughly tested every page after refactoring to ensure everything worked correctly.

---

## Conclusion

Today's session focused on improving the code structure of my Employee Management System. By creating a single **style.css** file and a single **custom.js** file, I made the project more organized, reusable, and easier to maintain. These improvements follow professional web development practices and will make future enhancements more efficient.

---

## Next Day Goal

- Add more features to the Employee Management System.
- Improve validation and user experience.
- Optimize the project for better performance.
- Continue learning advanced PHP and MySQL concepts.
