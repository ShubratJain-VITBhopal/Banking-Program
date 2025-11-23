# Banking-Program

## Overview of the Project 
This is a basic program written in Python that simulates banking functionality. The program allows users to check their balance, deposit money, and withdraw money, demonstrating foundational programming concepts like functions, loops, and input validation.

## Key Features 
* **Show Current Balance:** Displays the user's updated balance in a clear format.
* **Deposit Funds:** Allows the user to add money to the account, with validation to prevent negative deposits.
* **Withdraw Funds:** Allows the user to remove money, including checks for **insufficient funds** and negative amounts.
* **Menu-Driven Interface:** Simple, logical workflow for user interaction.

## Technologies Used 
* **Language:** Python 3.x
* **Version Control:** Git

## Installation and Setup 

1.  **Clone the Repository:**
    ```bash
    git clone [YOUR_GITHUB_REPO_URL]
    cd simple-banking-program
    ```
2.  **Run the Program:** Ensure you have Python 3 installed.
    ```bash
    python main.py
    ```
3.  **Start Interacting:** Follow the on-screen menu instructions (1-4).

## Instructions for Testing 
* **Test Case 1 (Successful Deposit):** Select option `2` and enter a positive amount (e.g., `500`). Verify the balance updates correctly by selecting option `1`.
* **Test Case 2 (Failed Withdrawal):** Select option `3` and attempt to withdraw an amount greater than the current balance (e.g., `1000`). Verify the "Insufficient Funds" error message appears and the balance remains unchanged.
* **Test Case 3 (Invalid Input):** Test option `2` or `3` and enter text or a negative number to verify the **Error Handling Strategy** functions correctly.

## Screenshots 
