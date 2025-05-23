# Smart Expense Tracker
#code for budget
""" http://127.0.0.1:8000/api/budget/

{
  "user": 1,
  "name": "April Budget",
  "total_amount": "500.00"
}

#code for expenses api
http://127.0.0.1:8000/api/expenses/

{
  "user": 1,
  "budget": 1,
  "description": "Groceries",
  "amount": 25
}
"""
# Smart Expense Tracker

Smart Expense Tracker is a Django-based application designed to help users manage their budgets and track expenses efficiently. It provides APIs for user authentication, budget management, and expense tracking.

## Features

- **User Authentication**: Secure user authentication using JWT tokens with `djoser`.
- **Budget Management**: Create and manage budgets.
- **Expense Tracking**: Add and track expenses associated with budgets.
- **RESTful API**: Fully functional REST API for integration with frontend or other services.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/smart-expense-tracker.git
   cd smart-expense-tracker