# Invoice Management System - Installation Guide

This guide provides step-by-step instructions to set up and run the **Invoice Management System** PHP project.

---

## How to Run?

### 1. **Download and Extract the Project**
   - Download the project files.
   - Extract the downloaded `.zip` file.

### 2. **Move Project Files to XAMPP Directory**
   - Navigate to your XAMPP installation directory.
   - Locate the `htdocs` folder inside the XAMPP directory.
   - Copy the extracted project folder (not the `.zip` file) into the `htdocs` folder.

### 3. **Set Up the Database**
   - Open your preferred web browser (Google Chrome or Mozilla Firefox recommended).
   - Go to the URL: `http://localhost/phpmyadmin`.
   - Create a new database with the name specified in the `01 LOGIN DETAILS & PROJECT INFO.txt` file (located in the project folder).
   - Click on the **Import** tab in phpMyAdmin.
   - Select the database file (`.sql`) from the folder named `DATABASE FILE` in the project directory.
   - Import the file to populate your database.

### 4. **Run the Project**
   - Go to the URL: `http://localhost/[ PROJECT_FOLDER_NAME ]/`
     - Replace `[ PROJECT_FOLDER_NAME ]` with the name of the folder you pasted into the `htdocs` directory.
   - Use the login credentials provided in the project folder (check the `01 LOGIN DETAILS & PROJECT INFO.txt` file).

---

## System Requirements
- **PHP Version**: 5.6 or newer
  - Note: This project does not support PHP versions older than 5.6. If you're using an older version, upgrade your PHP to avoid potential issues.
- **Database**: MySQL (set up via phpMyAdmin)
- **Web Server**: XAMPP or equivalent (with Apache and MySQL enabled)

---

## Additional Information
- This project provides an excellent learning opportunity for intermediate developers, offering insight into PHP and MySQL-based web applications.
- For any additional instructions or troubleshooting, refer to the files and documentation included in the project.

---

### License
This project is provided as-is with free source code for educational purposes. Feel free to explore, modify, and expand upon it.

Enjoy your journey into PHP web development! 🚀
