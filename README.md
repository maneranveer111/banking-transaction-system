🏦 Banking Transaction Tracking System (Console-Based)
📌 Project Overview

The Banking Transaction Tracking System is a Java-based console application that simulates core banking operations.
It allows users to register, log in, create a bank account, and perform transactions such as deposits, withdrawals, transfers, and viewing transaction history.

This project focuses on understanding backend fundamentals, layered architecture, and database-driven transaction handling using Java and JDBC.

🛠️ Tech Stack

Java (Core Java, OOP)

JDBC

MySQL

Console-based UI

🧱 Architecture

The project follows a layered architecture:

UI Layer        → Console interaction (MainApp.java)
Service Layer   → Business logic (UserService, AccountService, TransactionService)
DAO Layer       → Database access (UserDAO, AccountDAO, TransactionDAO)
Model Layer     → Entities (User, Account, Transaction)
Database        → MySQL


This structure ensures:

separation of concerns

easier maintenance

real-world backend design practices

✨ Features Implemented

User registration and login

Auto-generated User ID (handled by database)

Bank account creation

Deposit money

Withdraw money with balance validation

Transfer funds between users (using User ID)

View transaction history for logged-in users

Input validation and error handling

🔁 Application Flow

User registers with name, email, and password

User logs in using credentials

System displays auto-generated User ID

User creates a bank account

User can:

Check balance

Deposit money

Withdraw money

Transfer funds to another user

View transaction history

User logs out

⚠️ A bank account must be created before performing any transaction.

▶️ How to Run the Project

Clone or download the project

Create the required MySQL database and tables

Update database credentials in the DB connection utility

Run MainApp.java

Use the console menu to interact with the system

🧪 Sample Console Output
Login successful. Welcome Ranveer Mane (User ID: 1)

--- Transaction History ---
2026-01-18T03:32:17 | DEPOSIT | 1000
2026-01-18T03:33:05 | WITHDRAW | 200

📚 Learning Outcomes

Understanding layered backend architecture

Hands-on experience with JDBC and MySQL

Implementing transactional logic (deposit, withdraw, transfer)

Proper validation and null safety

Clear separation between User and Account concepts

Writing clean and maintainable Java code

🚧 Future Enhancements

Support multiple accounts per user

Implement transaction rollback for ACID compliance

Convert the application to a Spring Boot REST API

Develop a web-based frontend interface

👤 Author

Ranveer Mane
(Java Backend Learner)