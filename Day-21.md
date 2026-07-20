# Day 21 - Profile Picture Upload and Display Functionality

**Date:** 20 July 2026

## Overview

Today was the twenty-first day of my Web Development Training. The focus of today's session was on implementing the **Employee Profile Picture** feature in the Employee Management System.

I added functionality that allows employees to upload their profile pictures during registration. The uploaded images are stored in a dedicated folder on the server, while the image path is saved in the MySQL database using PHP. I also displayed the uploaded profile pictures on both the **Dashboard** and **Employee Information (info.php)** pages.

This enhancement made the Employee Management System more interactive and visually appealing by giving each employee a personalized profile.

---

## Topics Learned

### PHP File Upload

- File Upload using PHP
- HTML File Input (`<input type="file">`)
- Handling Uploaded Files
- `$_FILES` Superglobal
- Moving Uploaded Files using `move_uploaded_file()`
- File Storage Management
- Image Validation

### PHP and MySQL

- Storing Image Path in Database
- Retrieving Image Path
- Displaying Images Dynamically
- Database Integration with File Upload
- Managing User Profile Information

---

## Practical Work

During today's practical session, I:

- Added a profile picture upload field to the employee registration form.
- Implemented PHP file upload functionality.
- Stored uploaded images in a dedicated project folder.
- Saved the image path in the MySQL database.
- Retrieved the stored image path using PHP.
- Displayed the employee's profile picture on the Dashboard page.
- Displayed the profile picture on the Employee Information page.
- Tested the upload functionality with multiple employee accounts.

---

## Employee Management System Progress

Today I enhanced the Employee Management System by adding profile picture management.

### Features Implemented

- Employee Profile Picture Upload
- Image Storage in Project Folder
- Image Path Stored in MySQL Database
- Dynamic Image Display
- Profile Picture on Dashboard
- Profile Picture on Employee Information Page

### Workflow

1. Employee selects a profile picture during registration.
2. PHP receives the uploaded image using the `$_FILES` array.
3. The image is stored in the designated uploads folder.
4. The image path is saved in the MySQL database.
5. After login, PHP retrieves the stored image path.
6. The profile picture is displayed on the Dashboard page.
7. The same profile picture is also displayed on the Employee Information page.

---

## Key Learnings

- PHP can handle file uploads efficiently using the `$_FILES` superglobal.
- Uploaded files should be stored in a dedicated folder for better organization.
- Storing the image path instead of the image itself in the database is a common and efficient approach.
- Dynamic image retrieval allows personalized user profiles.
- File upload functionality is a useful feature in many real-world web applications.

---

## Challenges Faced

- Understanding the PHP file upload process.
- Saving uploaded images in the correct folder.
- Retrieving and displaying the correct profile picture for each employee.
- Ensuring the image path matched the stored database record.

---

## How I Overcame Them

- Practiced using PHP file upload functions.
- Verified that uploaded files were successfully stored in the designated folder.
- Checked the database to confirm that image paths were stored correctly.
- Tested the feature with different employee accounts to ensure each profile displayed the correct image.

---

## Conclusion

Today's session added an important personalization feature to the Employee Management System. I successfully implemented profile picture upload functionality using PHP, stored the uploaded images in a dedicated folder, and saved their paths in the MySQL database. The uploaded profile pictures are now displayed on both the Dashboard and Employee Information pages, making the application more professional, interactive, and closer to a real-world employee management system.

---

## Next Day Goal

- Add more advanced features to the Employee Management System.
- Improve validation and security for file uploads.
- Enhance the overall user interface and user experience.
- Continue learning advanced PHP and MySQL concepts.
