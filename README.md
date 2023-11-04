# Financial Transaction Recording System in Flask

This repository contains a simple financial transaction recording system developed in Flask, with basic Create, Read, Update and Delete (CRUD) operations. The system allows users to track financial transactions, including income and expenses, through an easy-to-use web interface.
# Live Demo: https://youtu.be/qpIh1SQY-3Q
## Features

### Read Transactions
- Access the main page ("/") to see all recorded transactions.

### Add Transactions
- Navigate to the "/add" path to add a new transaction using a form.

### Edit Transactions
- Access the path "/edit/<transaction_id>" to edit an existing transaction.

### Delete Transactions
- Use the path "/delete/<transaction_id>" to delete a specific transaction.

## Use

1. Make sure you have Flask installed. If you don't have it, install it using `pip install flask`.
2. Run the Flask application with the following command in the terminal:

    ```bash
    python app.py
    ```

3. Open a web browser and access `http://localhost:5000` to use the system.

## Code Structure

The code is organized as follows:

- **`app.py`**: Main file that contains the application logic.
- **`templates/`**: Directory that stores the HTML templates for the interface.
- **`static/`**: Folder for static resources such as CSS, JavaScript, etc.
- **`README.md`**: This file with information about the project.

## Contributions
Contributions are welcome! If you find areas for improvement, feel free to fork the repository, make changes, and submit pull requests.

## Grades
- The system uses a predefined list of transactions for demonstration. In a real environment, this information would be stored in a database.

**Note**: Make sure to replace `app.py` with the name of the file where your main code is located.

To run the application, simply run the mentioned file on your terminal and access `http://localhost:5000` in your browser.

Enjoy recording your financial transactions with this simple system in Flask!
