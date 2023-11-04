# Simple Flask Application

This is a simple Flask application that performs CRUD operations on a list of transactions.

## Libraries Used

```python
from flask import Flask, redirect, request, render_template, url_for
```

## Application Initialization

```python
app = Flask(__name__)
```

## Sample Data

The application uses a list of transactions as sample data.

```python
transactions = [
    {'id': 1, 'date': '2023-06-01', 'amount': 100},
    {'id': 2, 'date': '2023-06-02', 'amount': -200},
    {'id': 3, 'date': '2023-06-03', 'amount': 300}
]
```

## Routes

The application has the following routes:

- `@app.route("/")`: Lists all transactions.
- `@app.route("/add", methods=["GET", "POST"])`: Displays the form to add a transaction and handles the POST request to create a new transaction.
- `@app.route("/edit/<int:transaction_id>", methods=["GET", "POST"])`: Displays the form to edit a transaction and handles the POST request to update the transaction.
- `@app.route("/delete/<int:transaction_id>")`: Deletes a transaction.

## Running the Application

To run the application, use the following command:

```python
if __name__ == "__main__":
    app.run(debug=True)
```

This will start the Flask development server on your local machine.