# Banking System

## Description
This is a simple banking system in Java that allows users to create accounts, deposit and withdraw money, and display account details. The system supports two types of accounts:

1. **Savings Account**: Earns interest at a rate of 3% annually.
2. **Current Account**: Supports overdraft with a limit of ₹500.

The system uses object-oriented principles, including inheritance and abstraction, to manage different account types.

## Features
- **Create Savings Account**: Allows the creation of a savings account with an initial deposit.
- **Create Current Account**: Allows the creation of a current account with an initial deposit.
- **Deposit**: Allows depositing a specific amount to the selected account.
- **Withdraw**: Allows withdrawing from the selected account, subject to account type and balance conditions.
- **Show Account**: Displays the details of a specific account.
- **List All Accounts**: Displays the details of all created accounts.
- **Exit**: Exits the banking system.

## Requirements
- Java 8 or higher
- IDE such as IntelliJ IDEA or Eclipse to run the program

## How to Run
1. Clone or download the repository to your local machine.
2. Open the project in your preferred IDE.
3. Run the `Main.java` file.
4. Use the console to interact with the banking system.

## Class Overview

### `Main.java`
The entry point of the application, responsible for taking user input and performing various banking operations such as account creation, deposit, withdrawal, and displaying account details.

### `Account.java`
An abstract class representing a generic bank account. It contains common properties like account number, account holder name, and balance, along with methods for deposit and displaying account details.

### `SavingsAccount.java`
A subclass of `Account`, representing a savings account. It supports withdrawals and has an additional method to add interest to the balance.

### `CurrentAccount.java`
A subclass of `Account`, representing a current account. It supports withdrawals within an overdraft limit of ₹500.

### `Bank.java`
This class manages the accounts in the system, providing methods to add, get, and list accounts.

## Example Interaction

--- Banking System ---

1.Create Savings Account

2.Create Current Account

3.Deposit

4.Withdraw

5.Show Account

6.List All Accounts

7.Exit

Enter the choice: 1
Account Number: 12345
Holder Name: John Doe
Initial deposit: 5000
Account created successfully.

--- Banking System ---

1.Create Savings Account

2.Create Current Account

3.Deposit

4.Withdraw

5.Show Account

6.List All Accounts

7.Exit

Enter the choice: 3
Account Number: 12345
Amount to Deposit: 2000
Deposited: ₹2000