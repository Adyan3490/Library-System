# Library System

A command-line library management system written in Python.

This project was created to practise object-oriented programming, file handling, user authentication, and managing data through a command-line interface.

## Features

* User registration and login
* Separate user and administrator functionality
* Add, remove, search, and display books
* Borrow and return books
* Maximum borrowing limit of 5 books per user
* User management
* Transaction recording with timestamps
* Persistent data storage using text and CSV files

## How It Works

The system provides different functionality depending on whether the user logs in as a standard user or an administrator.

### Users

Users can:

* Search for books
* View available books
* Borrow books
* Return books
* View their borrowing information

### Administrators

Administrators can:

* Add books
* Remove books
* Search for books
* Display the library catalogue
* Manage users

## Project Structure

The system is organised around several Python classes:

* `Book` — represents books in the library
* `User` — manages standard user information and functionality
* `Admin` — provides administrator functionality
* `Library` — manages the library and its books
* `LoginSystem` — handles registration and login
* `Transactions` — records borrowing and returning activity

## Data Storage

The application uses local files to store information:

* `books.csv` — stores book information
* `users.txt` — stores user information
* `transactions.txt` — stores transaction records

This allows information to persist between program runs without requiring an external database.

## Running the Project

1. Clone the repository.
2. Open the project in a Python-compatible IDE.
3. Make sure the required data files are in the correct directory.
4. Run the main Python file.
5. Follow the instructions displayed in the command line.

## What I Learned

This project gave me experience with:

* Object-oriented programming in Python
* Classes and objects
* File input/output
* CSV data handling
* User authentication
* Command-line interfaces
* Program structure and modularity
* Designing a system using multiple interacting classes

## Project Background

This was an early programming project and represents my earlier experience with Python and software development.

The project is a simple command-line application rather than a production-level library management system.
