# CRUD_OPERATION
# CRUD Application with React, Express.js, and MySQL

This project implements a CRUD (Create, Read, Update, Delete) application for managing user data, allowing administrators to create, view, update, and delete user details like name, email, mobile number, and date of birth.

## Technologies Used

* **React:** A JavaScript library for building dynamic user interfaces. (https://legacy.reactjs.org/)
* **Express.js:** A Node.js framework for creating web applications. (https://expressjs.com/)
* **MySQL:** A relational database management system for storing and managing structured data. (https://www.mysql.com/)

## Features

The application provides a user-friendly interface for administrators to manage user data through the following CRUD operations:

* **Create:** Admins can add new users by providing their name, email, mobile number, and date of birth.
* **Read:** Admins can view a comprehensive list of all users currently stored in the database. Each user entry should display relevant information like name, email, and other desired details.
* **Update:** Admins can modify the details of existing users. This functionality typically involves retrieving a user's information for editing, making changes, and saving the updated data.
* **Delete:** Admins can remove unwanted users from the database. Consider implementing confirmation prompts to prevent accidental deletions.

## Getting Started

**Prerequisites:**

- Node.js and npm (or yarn) installed on your system (check with `node -v` and `npm -v`). You can download them from https://nodejs.org/en.
- A MySQL database server running (https://dev.mysql.com/downloads/mysql/).

**Steps:**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Abhishek5137/CRUD_OPERATION.git

cd crud-app
#Install Node.js dependencies using npm:
```
npm install

```

#Configure database connection:

## Edit server.js and update the following placeholders with your actual MySQL credentials:

```
const pool = mysql.createPool({
  host: 'your_hostname',
  user: 'your_username',
  password: 'your_password',
  database: 'your_database_name'
});

```
