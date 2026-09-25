📚 Online Bookstore

A full-stack Java web application for managing an online bookstore, including user registration, authentication, book browsing, shopping cart management, purchasing, payment receipts, and an administrative dashboard for inventory management.

Java Web Development Project — built with Java Servlets, JDBC, MySQL, HTML, CSS, JavaScript, and Bootstrap.

🚀 Project Overview

The Online Bookstore is a web-based e-commerce application designed to provide a simple and user-friendly platform for purchasing books online.

The application supports two types of users:

Customers — browse books, select quantities, purchase books, and receive payment receipts.

Administrators — manage books, inventory, pricing, and sales information.

The project demonstrates practical implementation of Java Servlets, JDBC, MVC-style web application development, database connectivity, session management, and CRUD operations.

✨ Key Features

👤 Customer Features

User registration and login

Browse available books

View book details and prices

Select books and quantities

Add books to the shopping cart

Purchase books

Generate payment receipts

View purchase-related information



🔐 Administrator Features

Secure administrator login

Add new books

View available books

Remove books

Increase or decrease inventory

Update book prices

Manage book availability

Maintain selling history

🛠️ Technology Stack
Layer	Technologies
Frontend	HTML, CSS, JavaScript, Bootstrap
Backend	Java, Java Servlets, JDBC
Database	MySQL
Build Tool	Apache Maven
Application Server	Apache Tomcat
IDE	Eclipse Enterprise Edition
Version Control	Git & GitHub
🏗️ Application Architecture

The application follows a layered web-application approach:

User
  │
  ▼
HTML / CSS / JavaScript / Bootstrap
  │
  ▼
Java Servlets
  │
  ▼
JDBC
  │
  ▼
MySQL Database

Main Components

Presentation Layer — HTML, CSS, JavaScript, and Bootstrap

Controller Layer — Java Servlets handling HTTP requests

Data Access Layer — JDBC for database operations

Database Layer — MySQL for users, books, inventory, and related data

🗄️ Database

The application uses MySQL with tables for:

Users

Books

Inventory

User roles

Example book data includes:

Book barcode/ISBN

Book name

Author

Price

Available quantity

📸 Screenshots
Online Bookstore

Book Management

<!-- Add additional screenshots here as your updated UI screenshots become available. -->
⚙️ Running the Project Locally
Prerequisites

Install the following:

Java JDK 8 or higher

Eclipse Enterprise Edition

Apache Maven

Apache Tomcat 8.0+

MySQL Server

MySQL Workbench (optional)

Git

1. Clone the Repository
git clone https://github.com/jasmine-4/onlinebookstore.git
cd onlinebookstore

2. Configure the Database

Create the database:

CREATE DATABASE onlinebookstore;
USE onlinebookstore;


Create the required tables and insert the sample data using the SQL script provided in the project.

3. Configure Database Connection

Open:

src/main/resources/application.properties


Update the database configuration with your local MySQL credentials.

Example:

db.username=YOUR_USERNAME
db.password=YOUR_PASSWORD


Do not commit real database passwords or other credentials to GitHub.

4. Build the Project

Run:

mvn clean install

5. Deploy to Tomcat

Deploy the generated application to Apache Tomcat and start the server.

The application can then be accessed locally at:

http://localhost:8083/onlinebookstore/


The port may differ depending on your local Tomcat configuration.

🔑 Demo Accounts

For local/demo purposes, sample accounts can be created using the database initialization script.

Customer

Username: jasmine
Password: jasmine


Administrator

Username: Admin
Password: Admin


These credentials are intended only for the sample project. For a production application, passwords should never be stored or shared in plain text.

📂 Project Structure
onlinebookstore/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── ...
│       └── resources/
│           └── application.properties
│
├── WebContent/
│   ├── bookstore.jpeg
│   ├── books.jpg
│   └── ...
│
├── pom.xml
└── README.md

🔒 Security Note

This project was developed as a learning/mini-project and does not implement all security practices required for production applications.

Potential production improvements include:

Password hashing

Secure session management

Input validation

CSRF protection

Authentication/authorization improvements

Secure database configuration

HTTPS

Environment-based secrets management

🔮 Future Improvements

Potential enhancements include:

Online payment gateway integration

Book search and filtering

Book categories

User order history

Wishlist functionality

Email notifications

Password reset functionality

REST API integration

Improved authentication and authorization

Responsive UI improvements

Automated testing

Docker-based deployment

Cloud deployment

🎯 Skills Demonstrated

This project demonstrates practical experience with:

Java web development

Java Servlets

JDBC

MySQL database design

CRUD operations

HTTP request/response handling

User authentication

Session management

Role-based application functionality

MVC-style application development

HTML/CSS/JavaScript

Bootstrap

Maven

Apache Tomcat

Git/GitHub

👩‍💻 Author

Jasmine Mohal

Java Developer | Web Development | Backend Development

⭐ If you found this project useful, feel free to explore the repository and provide feedback.
