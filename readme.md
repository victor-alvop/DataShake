# DataShake Project - Flask

This project is a web application built with Flask that interacts with two databases: a source database (`db_source`) and a target summary database (`db_target`). The application allows you to perform data transformations such as concatenation, replacement, case conversion, and numeric operations on employee data. It also includes features for obtaining aggregated summaries like employee count, average salary, and average hours per department.

## Features

- **View Employees and Summaries**: Displays employees and their summaries in real-time from the databases.
- **Employee Insertion Form**: Allows you to add new employees to the database.
- **Data Transformations**:
  - Concatenate text in columns.
  - Replace text in columns.
  - Convert text to lowercase or uppercase.
  - Perform numeric operations (sum, subtraction, multiplication, division) on numeric columns.
- **Aggregated Summaries**:
  - Count employees per department.
  - Calculate the average salary per department.
  - Calculate the average hours worked per department.

## Requirements

- Python 3.x
- Flask
- SQLAlchemy
- PostgreSQL or any other SQLAlchemy-compatible database engine

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your_username/your_repository.git
   cd your_repository

2. **Create virtual enviroment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # For macOS/Linux

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    
4. **Setup databases**
Make sure you have the databases set up and the necessary tables (you can use PostgreSQL or any compatible database engine with SQLAlchemy).

5. **Run the App**
    ```bash
    flask run

The app will be available at http://127.0.0.1:5001/.





