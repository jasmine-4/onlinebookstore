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
  1. User registration and login
  2. Browse available books
  3. View book details and prices
  4. Select books and quantities
  5. Add books to the shopping cart
  6. Purchase books
  7. Generate payment receipts
  8. View purchase-related information

🔐 Administrator Features
  1. Secure administrator login
  2. Add new books
  3. View available books
  4. Remove books
  5. Increase or decrease inventory
  6. Update book prices
  7. Manage book availability
  8. Maintain selling history

🛠️ Technology Stack
Frontend    ->	  HTML, CSS, JavaScript, Bootstrap
Backend	    ->   Java, Java Servlets, JDBC
Database	  ->   MySQL
Build Tool	-> Apache Maven
Application -> Apache Tomcat
IDE        	-> Eclipse Enterprise Edition
Version     ->  Control	Git & GitHub

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
  1. Presentation Layer — HTML, CSS, JavaScript, and Bootstrap
  2. Controller Layer — Java Servlets handling HTTP requests
  3.Data Access Layer — JDBC for database operations
  4. Database Layer — MySQL for users, books, inventory, and related data

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
  ![Online Book Store](WebContent/bookstore.jpeg)
  
⚙️ Running the Project Locally
Prerequisites
Install the following:

 - Java JDK 8 or higher
 - Eclipse Enterprise Editior
 - Apache Maven 
 - Apache Tomcat 8.0+
 - MySQL Server
 - MySQL Workbench (optional)
 - Git

1. Clone the Repository
  git clone https://github.com/jasmine-4/onlinebookstore.git
  cd onlinebookstore

2. Configure the Database
   - Create a MySQL database named onlinebookstore and execute the SQL initialization script provided in this repository.

  2. Create the required tables and insert the sample data using the SQL script provided in the project.

3. Configure Database Connection
    Open: src/main/resources/application.properties
    Update the database username, password, host, and other connection settings according to your local MySQL configuration.
    Note: Do not commit real database passwords or other sensitive credentials to GitHub.

5. Build the Project
   - Run: mvn clean install

5. Run with Apache Tomcat
    Deploy the application to Apache Tomcat and start the server.
    Once Tomcat is running, open:
    http://localhost:8083/onlinebookstore/

🔑 Demo Accounts
For testing the application locally, you can use the sample accounts provided in the database initialization script.

Customer
  Username: jasmine
  Password: jasmine

Administrator
  Username: Admin
  Password: Admin

These credentials are for local/demo purposes only. Use secure, hashed passwords in a production application.

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

🎯 Skills Demonstrated
This project demonstrates practical experience with:

  - Java web development
  - Java Servlets
  - JDBC
  - MySQL database design
  - CRUD operations
  - HTTP request/response handling
  - User authentication
  - Session management
  - Role-based application functionality
  - MVC-style application development
  - HTML/CSS/JavaScript
  - Bootstrap
  - Maven
  - Apache Tomcat
  - Git/GitHub

👩‍💻 Author
Jasmine Kaur Mohal

Java Developer | Web Development | Backend Development

