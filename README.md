#Project Description
The "ATM Management System" is a Java-based application that simulates the core functionalities of an Automated Teller Machine (ATM).  
It allows users to perform essential banking operations such as "balance inquiry, cash deposit, cash withdrawal, mini statement viewing, and PIN management" securely.

This project demonstrates how "Java" can be integrated with a "MySQL database" using "JDBC" for efficient data storage and retrieval.  
It follows the "Object-Oriented Programming (OOP)" approach and provides  "user" functionalities.

## Tech Stack

| Component | Technology |
|------------|-------------|
| Programming Language | Java |
| Database | MySQL |
| Connectivity | JDBC (Java Database Connectivity) |
| IDE | NetBeans |

## Features

###  User Features

 1. Secure Login using Account Number and PIN

Users must log in with their unique account number and personal identification number (PIN) to access the system.
This ensures that only authorized users can perform banking operations.
All login details are verified securely from the MySQL database, and invalid attempts are restricted to prevent unauthorized access.

2. Balance Inquiry

After successful login, users can check their current account balance at any time.
The system fetches the balance directly from the MySQL database in real-time, ensuring accuracy after every transaction (deposit or withdrawal).

3. Cash Withdrawal

Users can withdraw money from their account by entering the desired amount.
Before processing, the system verifies:
Whether the account has sufficient funds.
After successful withdrawal, the balance is updated in the database and a transaction record is stored."

4. Cash Deposit

Users can deposit cash into their account.
Once the deposit amount is entered, the system adds the amount to the existing balance in the MySQL database.
A corresponding transaction record is also created, showing the type as “Deposit”, amount, and timestamp.

5. PIN Change

Users can update their ATM PIN for security reasons.
The system asks for the current PIN and then the new PIN twice for confirmation.
Once verified, the updated PIN is securely stored in the database (you can enhance this with encryption for extra security).
- "Mini Statement" (View recent transactions)

Mini Statement (Recent Transactions)

The system provides a mini statement feature that displays the last few transactions made by the user.
It shows details like:
- Transaction Type (Deposit / Withdrawal)
- Amount
- Date and Time
- Balance after each transaction
 This feature helps users keep track of their recent banking activities.

Database Management: All data is stored and retrieved from a MySQL database to ensure accuracy and consistency.

Error Handling & Validation: Ensures smooth operation and prevents invalid transactions.

### 💾 Database Features
- MySQL database for data storage and management
- Transaction records with timestamps.
