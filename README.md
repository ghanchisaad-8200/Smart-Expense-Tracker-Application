# Smart Expense Tracker Application

## 📌 Project Overview

The **Smart Expense Tracker Application** is a Python-based project designed to record, manage, analyze, and visualize personal expenses. It helps users understand their spending habits by organizing expenses into categories and calculating important financial statistics.

This project demonstrates Python programming concepts, Object-Oriented Programming (OOP), data analysis, and data visualization.

## 🎯 Project Objectives

- Record expenses with date, amount, category, and description.
- Validate expense amounts and categories.
- Manage expense records using a Python class.
- Calculate total and average spending.
- Analyze expenses by category and month.
- Identify the top spending category and month.
- Visualize spending patterns using charts.

## ✨ Features

### 1. Expense Input and Validation
- Accepts expense details from the user.
- Checks that the expense amount is positive.
- Allows four predefined categories:
  - Food
  - Transport
  - Utilities
  - Entertainment

### 2. Expense Management Using OOP
- Uses the `ExpenseTracker` class.
- Adds new expense records to a Pandas DataFrame.
- Saves updated records to a CSV file.
- Filters expenses by category.
- Calculates total and average expenses.

### 3. Expense Analysis
- Loads and manages data using Pandas.
- Uses NumPy for numerical calculations.
- Checks for missing values and removes rows containing them.
- Groups expenses by category and month.
- Identifies the highest-spending category and month.

### 4. Data Visualization
- **Bar Chart:** Displays total expenses by category.
- **Histogram:** Shows the frequency distribution of expense amounts.

## 🛠️ Technologies Used

- **Python 3** — Programming language
- **NumPy** — Numerical calculations
- **Pandas** — Data manipulation and analysis
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical charts
- **Jupyter Notebook** — Interactive coding environment
- **CSV** — Expense data storage

## 📂 Project Structure

```text
Smart-Expense-Tracker/
│
├── Smart_Expense_Tracker.ipynb
├── expenses.csv
└── README.md
```

`expenses.csv` is the data file used by the notebook. Add this file before running the analysis and expense-management sections.

The CSV file should contain these column names:

```text
Date,Amount,Category,Description
```

## ⚙️ Installation and Setup

### Step 1: Install Python

Install Python 3 on your computer if it is not already installed.

### Step 2: Install Required Libraries

Open your terminal or command prompt and run:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### Step 3: Download or Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### Step 4: Open the Project

Navigate to the project folder and start Jupyter Notebook:

```bash
jupyter notebook
```

Open `Smart_Expense_Tracker.ipynb` in your browser.

### Step 5: Run the Notebook

Execute the notebook cells in order. Ensure that `expenses.csv` exists in the same folder before running cells that load the CSV file.

## 💻 Example Expense Data

| Date | Amount | Category | Description |
|---|---:|---|---|
| 2026-01-10 | 250 | Food | Lunch |
| 2026-01-11 | 100 | Transport | Bus fare |
| 2026-01-12 | 500 | Utilities | Electricity |
| 2026-01-13 | 200 | Entertainment | Movie |

*These are sample records for demonstration.*

## 📚 Python Concepts Covered

- Variables and data types
- Lists and arrays
- Loops and conditional statements
- User input and validation
- Functions and methods
- Classes and objects
- NumPy arrays and mathematical operations
- Pandas DataFrames and grouping
- CSV file handling
- Data visualization

## 🚀 Future Improvements

- Add date-range filtering.
- Generate monthly expense reports.
- Export reports to Excel or PDF.
- Add a graphical user interface.
- Add a monthly budget and budget alerts.
- Store and manage expenses in a database.

## 🎓 Learning Outcomes

This project provides practical experience in Python programming, data validation, object-oriented programming, data analysis, and visualization. It demonstrates how Python libraries can be combined to build a basic expense-tracking and reporting application.

## 👨‍💻 Author

**Saad Ghanchi**

GitHub: [ghanchisaad-8200](https://github.com/ghanchisaad-8200)

---

⭐ If you find this project useful, consider giving the repository a star!
