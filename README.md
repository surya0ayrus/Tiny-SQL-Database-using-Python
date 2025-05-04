# Tiny SQLite Sales Summary using Python

A simple Python project that connects to a SQLite database, runs basic sales summary queries using SQL, and visualizes the results with a bar chart using `matplotlib`.

## 🔍 Objective

Use SQL within Python to:
- Retrieve total quantity sold and total revenue by product
- Display the results using `print()`
- Plot a simple bar chart for revenue by product

## 🧰 Tools Used

- **Python**
- **SQLite3** (built-in)
- **pandas** for data handling
- **matplotlib** for plotting
- **Jupyter Notebook** or `.py` script

## 🗃️ Dataset

- A small SQLite database named `sales_data.db`
- Contains a single table: `sales`
- Sample schema:
  ```sql
  CREATE TABLE sales (
      id INTEGER PRIMARY KEY,
      product TEXT,
      quantity INTEGER,
      price REAL
  );
