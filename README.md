# Expense Tracker

A simple command-line Expense Tracker application built using Python.  
This project helps users manage their budget by adding expenses, viewing spending details, and saving data permanently using a JSON file.

---

## Features

- Add expenses with description and amount
- View total budget and remaining balance
- Automatically calculates total expenses
- Saves expense data in a JSON file
- Loads previous data when the application starts
- Beginner-friendly command-line interface

---

## Technologies Used

- Python
- JSON File Handling

---

## Project Structure

```text
expense_tracker/
│
├── tracker.py
├── budget_data.json
└── README.md
```

---

## How It Works

1. User enters an initial budget
2. Expenses can be added anytime
3. The application stores:
   - Expense descriptions
   - Expense amounts
4. Budget data is saved in `budget_data.json`
5. Previous data is automatically loaded on next launch

---

## Installation

### Clone the repository

```bash
git clone https://github.com/Avinash-Singh-Sachan/expense_tracker.git
```

### Navigate to the project directory

```bash
cd expense_tracker
```

### Run the application

```bash
python tracker.py
```

---

## Example Usage

```text
Welcome to the Budget App

What would you like to do?

1. Add an expense
2. Show budget details
3. Exit
```

---

## Future Improvements

- Add expense categories
- Monthly expense reports
- Data visualization using graphs
- GUI version using Tkinter or PyQt
- Expense editing and deletion
- Database integration

---

## Learning Outcomes

This project demonstrates:
- Functions in Python
- File handling
- JSON serialization/deserialization
- Loops and conditionals
- Modular programming
- Basic CLI application development

---

## Author

GitHub: https://github.com/Avinash-Singh-Sachan
