# Library Management System

This is a Library Management System built with Flask for the backend and HTML, CSS, and JavaScript for the frontend. The system allows users to manage books, customers, and loans.

## Features

- Add, view, search, and delete books
- Add, view, search, and delete customers
- Manage loans and track overdue loans

## Technologies Used

- Flask
- Flask-CORS
- Flask-SQLAlchemy
- SQLite
- HTML
- CSS (Bootstrap)
- JavaScript (Axios)

## Setup Instructions

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/shalevshakir/Library-with-axios-and-flask.git
   
2. **install the packages:**

   ```sh
   pip install -r requirements.txt
   



# API Endpoints

## Books

- **GET /books**: Retrieve all books that are not deleted
- **GET /books/available**: Retrieve all available books that are not deleted
- **POST /books**: Add a new book
- **DELETE /books/{book_id}**: Mark a book as deleted

## Customers

- **GET /customers**: Retrieve all customers that are not deleted
- **GET /customers/active**: Retrieve all active customers that are not deleted
- **POST /customers**: Add a new customer
- **DELETE /customers/{customer_id}**: Mark a customer as deleted

## Loans

- **GET /loans/non-overdue**: Retrieve all non-overdue loans
- **POST /loans**: Add a new loan
- **PUT /loans/return/{loan_id}**: Mark a loan as returned
- **GET /loans/overdue**: Retrieve all overdue loans