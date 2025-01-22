# Expense Tracker

## Overview
This is a Python-based command-line application designed to help users track and manage their expenses. The program allows users to add, view, filter, remove, save, and load expenses.

## Features
- **Add Expense:** Users can record an expense with a description, category, amount, and date.
- **Display Summary:** Provides a total of all expenses and a breakdown by category.
- **Filter by Date:** View expenses within a specific date range.
- **Remove Expense:** Allows removal of expenses by description or date.
- **Save and Load Expenses:** Save the expense records to a file and load them back when needed.

## Usage
1. Run the script.
2. Use the menu to:
   - Add a new expense.
   - View a summary of expenses.
   - Filter expenses by date.
   - Remove expenses by description or date.
   - Save expenses to a file.
   - Load expenses from a file.
3. Follow the prompts to input the required information.

## Code Overview
- **ExpenseTracker Class:**
  - Manages a list of expenses with methods for adding, removing, and summarizing data.
  - Handles file operations for saving and loading expenses.
- **Main Menu:**
  - Provides an interactive interface for users to manage their expenses.

## Example Interaction
```
Expense Tracker
1. Add Expense
2. Display Summary
3. Display Expenses by Date
4. Remove Expense
5. Save Expenses
6. Load Expenses
7. Exit
Choose an option: 1
Enter expense description: Groceries
Enter expense category: Food
Enter expense amount: 250
Enter expense date (YYYY-MM-DD): 2025-01-20
Expense added successfully.
```
