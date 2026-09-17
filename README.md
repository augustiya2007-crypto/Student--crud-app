Student Management System – CRUD Web Application

Project Overview

The Student Management System is a web-based CRUD application developed to manage student information. The system allows users to add, view, update, and delete student records through a simple and user-friendly interface.

Objectives

- To create a simple student management application.
- To implement CRUD operations.
- To connect the frontend with a backend REST API.
- To store student information in a database.
- To implement input validation and error handling.
- To test the application using Postman.

Features

- Add new student records
- View all student records
- View individual student details
- Update student information
- Delete student records
- Search student records
- Form validation
- REST API integration
- SQLite database storage

Technology Stack

Component| Technology
Frontend| HTML, CSS, JavaScript
Backend| Python Flask
API| REST API
Database| SQLite
API Testing| Postman
Version Control| Git and GitHub

Student Details

The application stores the following information:

- Student ID
- Name
- Email
- Department
- Attendance
- Marks
- Study Hours

CRUD Operations

Operation| HTTP Method| Description
Create| POST| Add a new student
Read| GET| View student records
Update| PUT| Update an existing student
Delete| DELETE| Delete a student

API Endpoints

GET    /api/students
GET    /api/students/<id>
POST   /api/students
PUT    /api/students/<id>
DELETE /api/students/<id>

Project Structure

student-crud-app/
│
├── app.py
├── requirements.txt
│
├── templates/
│   └── index.html
│
└── static/
    ├── style.css
    └── script.js

Installation and Execution

1. Clone the repository

git clone <your-github-repository-url>

2. Open the project folder

cd student-crud-app

3. Install required packages

pip install -r requirements.txt

4. Run the application

python app.py

5. Open the application

Open the URL shown in the terminal, usually:

http://127.0.0.1:5000

Testing

The REST API can be tested using Postman.

The following operations are tested:

- POST – Create student
- GET – Read students
- PUT – Update student
- DELETE – Delete student

Validation is also tested using empty, invalid, duplicate, and incorrect input values.

Database

SQLite is used to store student records. The database contains a "students" table with fields for student ID, name, email, department, attendance, marks, and study hours.

Future Enhancements

- User authentication and login
- Student performance prediction
- Advanced search and filtering
- Dashboard with charts
- Export student data
- Deployment to a cloud platform

Conclusion

The Student Management System demonstrates a complete CRUD-based web application. It integrates a frontend, backend REST API, and database to perform student record management. The project also includes validation, API testing, and version control using GitHub.

Author

Augustiya K
B.Tech – Artificial Intelligence and Data Science
VSB Engineering College, Karur
