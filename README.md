
# Bank Management System

A console-based Bank Management System developed using Java, Object-Oriented Programming (OOPs), JDBC, and PostgreSQL. The application allows users to register, log in, manage bank accounts, and perform basic banking transactions.

## Technologies Used

- Java
- Object-Oriented Programming (OOPs)
- JDBC (Java Database Connectivity)
- PostgreSQL
- SQL

## Features

- **User Registration:** Register new users with their name, email, and password.
- **User Login:** Authenticate users using email and password.
- **Account Creation:** Open a bank account with an initial deposit and security PIN.
- **Credit Money:** Deposit money into an existing bank account.
- **Debit Money:** Withdraw money after PIN verification and balance validation.
- **Money Transfer:** Transfer funds between bank accounts.
- **Check Balance:** View account balance after security PIN verification.

## Project Structure

Bank-Management-System/
│
├── src/
│   ├── BankingApp.java
│   ├── User.java
│   ├── Accounts.java
│   └── AccountManager.java
│
├── database/
│   └── schema.sql
│
├── .gitignore
└── README.md

## Database Setup

1. Install PostgreSQL on your system.
2. Create a database named `BankingManagementSystem`.
3. Execute the SQL queries provided in `database/schema.sql` to create the required tables.
4. Configure your PostgreSQL database credentials in the application.

## JDBC Configuration

Add the PostgreSQL JDBC driver to your project.

Update the database connection details in `BankingApp.java` according to your local PostgreSQL configuration.

## How to Run

1. Clone this repository:

   git clone <your-repository-url>

2. Open the project in your preferred Java IDE.
3. Configure the PostgreSQL database and JDBC driver.
4. Run `BankingApp.java`.
5. Follow the console menu to register, log in, and perform banking operations.

## Concepts Implemented

- Classes and Objects
- Encapsulation
- Constructors
- Methods and Object Interaction
- JDBC Database Connectivity
- PreparedStatement and ResultSet
- SQL CRUD Operations
- Exception Handling
- Database Transaction Management (Commit and Rollback)

## Future Improvements

- Password hashing and secure PIN storage.
- Improved input validation.
- Transaction history.
- Account statement generation.
- Enhanced exception handling.

## Author

Alok Kumar
