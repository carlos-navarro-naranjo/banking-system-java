# Banking System in Java
Developed a console-based banking system in Java using object-oriented programming principles. Implemented customer account creation, checking/savings account management, deposits, withdrawals, and exception handling for insufficient funds.


A simple console-based banking application built in Java using object-oriented programming principles.

---

## Features

- Create customer accounts
- Open checking and savings accounts
- Deposit money into accounts
- Withdraw money from accounts
- View customer and account information
- Exception handling for insufficient funds
- Console-based user interaction

---

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Eclipse / IntelliJ IDEA
- Java Scanner Class
- Exception Handling

---

## Project Structure

```text
src/
└── banking/
    ├── Bank.java
    ├── BankAccount.java
    └── Customer.java
```

---

## How the Program Works

1. User enters their name
2. User enters their address
3. Program creates:
   - Checking account
   - Savings account
4. User deposits money into both accounts
5. User withdraws money from accounts
6. Program displays updated balances
7. Exception handling prevents overdrawing

---

## Example Output

```text
Welcome to the Bank! What is your name?

Carlos

Hello Carlos! We are creating checking and savings accounts for you.

What is your address?

Dallas

Customer info:
Carlos from Dallas

Checking account:
checking: 0.0

Savings account:
savings: 0.0

Amount (decimal) to deposit into your checking account?
500

Amount (decimal) to deposit into your savings account?
300

checking: 500.0
savings: 300.0

Amount (decimal) to withdraw from your checking account?
200

Amount (decimal) to withdraw from your savings account?
100

checking: 300.0
savings: 200.0
```

---

## Object-Oriented Concepts Demonstrated

- Classes and Objects
- Constructors
- Methods
- Encapsulation
- Object Relationships
- Exception Handling
- Packages in Java

---

## Future Improvements

- Add graphical user interface (GUI)
- Add transaction history
- Add account authentication/login
- Save account data to files or database
- Add interest calculations
- Support multiple customers

---

## Author

Created by Carlos Navarro Naranjo
