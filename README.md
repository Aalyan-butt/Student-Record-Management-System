# Student Record Management System

A simple and efficient **Student Record Management System** built using **PHP** and **MySQL**. This system allows administrators to manage student data, including adding, updating, and deleting student records. The system also provides an intuitive and user-friendly interface for viewing student information.

## Features

- **Student Record Management**: Easily add, update, delete, and view student records.
- **Admin Dashboard**: Secure admin panel for managing student data with authentication.
- **Database-Driven**: MySQL for storing and retrieving student records.
- **Responsive UI**: Simple, clean, and responsive user interface for easy navigation on all devices.

## Prerequisites

Before running the project, ensure the following requirements are met:

- **XAMPP/WAMP/LAMP** installed on your system.
- **PHP 7.0 or higher** for server-side scripting.
- **MySQL** or **MariaDB** server to manage the database.

## How to Run the Project

Follow the steps below to set up the **Student Record Management System** on your local server:

### 1. Download the Project

Download the project zip file from the repository, and extract the contents to obtain the `studentrecordms` folder.

### 2. Extract the Zip File

After downloading, extract the zip file to get the project folder (`studentrecordms`).

### 3. Move the Project to the Root Directory

Move the `studentrecordms` folder to your web server’s root directory:

- For **XAMPP**, paste it in `xampp/htdocs/`.
- For **WAMP**, paste it in `wamp/www/`.
- For **LAMP**, paste it in `var/www/html/`.

### 4. Set Up the Database

1. Open **PHPMyAdmin** by navigating to `http://localhost/phpmyadmin` in your browser.
2. Create a new database named `studentrecorddb`.
3. Import the `studentrecorddb.sql` file located in the `SQL` folder within the project directory to create the necessary tables.

### 5. Access the Project

After setting up the database, access the project by navigating to `http://localhost/studentrecordms` in your browser.

### 6. Admin Login

Use the following credentials to log in as the admin:

- **Username**: `admin`
- **Password**: `Test@12345`

---

## Technologies Used

This project was built using the following technologies:

- **PHP**: Server-side scripting language for backend development.
- **MySQL**: Database to store and manage student records.
- **HTML/CSS**: Front-end for creating the user interface.
- **JavaScript/jQuery**: Added functionality and interactivity to the website.
- **Bootstrap**: Front-end framework used to ensure responsive design for all screen sizes.

## Contributing

We welcome contributions to the **Student Record Management System**! If you'd like to contribute, please:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Submit a pull request with a description of the changes you made.

## Acknowledgments

- A huge thank you to the contributors and resources that made the development of this project possible.

---

**Enjoy managing your student records with this simple yet effective management system!**
