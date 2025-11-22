Expense Tracker (Python CLI)
Overview
This is a simple command-line Python application that helps you record, view, and analyze personal expenses. Users can log amounts and categories, review all entries, see total spending, and generate category-wise summaries.

# Features
Add expenses with amount and category (Food/Travel/Shopping/Bills/Others)

View all logged expenses

Display total spending

Provide summary of spending per category

# Requirements
Python 3.x (no additional libraries required)

# Setup Instructions
Clone the repository

bash
git clone https://github.com/yourusername/python-expense-tracker.git
Navigate to the project directory

bash
cd python-expense-tracker
Run the application

bash
python expense_tracker.py
Usage
When you run the script, you'll see the following menu:

# choices you get
==== Expense Tracker ====
1. Add Expense
2. View All Expenses
3. Total Expenses
4. Category Summary
5. Exit
Select an option by entering its number.

Follow prompts to add expenses or view summaries.

# Code Details
expense_tracker.py: Main script. All features are implemented in this file.

add_expense(): Adds a new expense entry with amount and category.

view_expenses(): Displays all recorded expenses in a list.

total_expenses(): Calculates and prints the total amount spent

category_summary(): Shows total expenses grouped by category.




