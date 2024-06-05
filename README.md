# Codealpha_Task-2
The provided Java program, SimpleBankingApp, is a basic banking application that allows a user to perform simple banking operations: depositing money, withdrawing money, and checking the current balance. The application runs in a loop until the user chooses to quit. Here's a breakdown of its main components and functionality:

Components and Functionality
Main Method:

Initializes a Scanner object for user input.
Displays a welcome message.
Enters a loop that continues until the user decides to quit.
Provides a menu with options to deposit, withdraw, check balance, or quit.
Calls the appropriate method based on the user's choice.
Deposit Method:

Prompts the user to enter an amount to deposit.
Validates that the amount is positive.
Adds the amount to the balance if valid.
Prints a success message with the new balance or an error message if the amount is invalid.
Withdraw Method:

Prompts the user to enter an amount to withdraw.
Validates that the amount is positive and does not exceed the current balance.
Subtracts the amount from the balance if valid.
Prints a success message with the new balance or an error message if the amount is invalid or if there are insufficient funds.
Check Balance Method:

Prints the current balance.
Quit Option:

Exits the loop and terminates the program.
Prints a thank-you message before closing.
Key Points
