# Task 2: Multi-User Bank Transaction Summary

This Python script collects and summarizes bank transaction data for **multiple users**. It allows each user to enter:

- Their **name**
- **Starting balance**
- A list of **transactions**, where each transaction includes:
  - **Amount**
  - **Type** (credit or debit)
  - **Description** (e.g., "Salary", "Grocery", etc.)

### Features:
- Stores data in a **dictionary**, with each user as a key and their data as values.
- Each user's transactions are stored as a **list of tuples**.
- Calculates the **final balance** after all transactions.
- Allows selection of a user to display their **detailed transaction summary**.
- Optionally displays **all stored user data** currently in memory.

### To Run:
```bash
python bank_transaction_summary.py