This is a basic banking application built in Java. It allows the user to perform basic banking operations like deposit, withdraw, check balance and exit.

##Features

- Deposit money
- Withdraw money
- Check account balance
- Exit application

## Usage

On running the application, the user is presented with a menu:

1. Deposit
2. Withdraw
3. Check Balance  
4. Exit

The user can choose options by entering the number corresponding to the operation they wish to perform.

To deposit money, enter 1 and the amount to deposit. This will add to the account balance.

To withdraw money, enter 2 and the amount to withdraw. This will deduct from the account balance if sufficient funds are available, else it will print "Insufficient funds!".

To check current account balance, enter 3. This will print the current balance.

To exit the application, enter 4. This will terminate the program.

## Code Overview

- `balance` variable stores account balance value
- `Scanner` used to get input from user
- `while(true)` loop for repetitive operations
- `switch-case` implements the menu options
- Methods like `deposit()`, `withdraw()` modify `balance` variable
- `System.out.print()` and `println()` used for input and output

## Future Improvements

- Add support for multiple accounts per user
- Implement classes for Accounts, Users
- Add database persistence for transactions and balances
- Improve validation on user inputs
- Implement better APIs for withdrawal, deposit etc.
- Add support for money transfer between accounts
