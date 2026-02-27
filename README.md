ATM Withdrawal Validator
📌 Project Overview

This project is a beginner-friendly Python program that simulates ATM withdrawal validation. It checks whether a withdrawal request satisfies standard banking conditions before approving the transaction.

🚀 Features

✔ Accepts account balance and withdrawal amount as user input
✔ Ensures withdrawal amount is a multiple of ₹100
✔ Ensures minimum balance of ₹1000 remains after withdrawal
✔ Displays appropriate validation messages
✔ Uses conditional statements and logical operators

🧠 Logic Used

The program validates withdrawal using the following conditions:

amount % 100 == 0 → Withdrawal must be multiple of 100

balance - amount >= 1000 → Minimum ₹1000 must remain

Displays proper error message if conditions fail
