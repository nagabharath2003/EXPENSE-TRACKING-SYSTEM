# EXPENSE-TRACKING-SYSTEM

## Overview

Expense Manager is a simple and easy-to-use application that helps you track your daily expenses. It allows you to add, view, delete, and analyze your expenses efficiently. The application is built using MySQL for the database and Streamlit for the frontend, ensuring a smooth user experience.


### Streamlit  <img src="https://user-images.githubusercontent.com/7164864/217935870-c0bc60a3-6fc0-4047-b011-7b4c59488c91.png" alt="Streamlit logo" style="margin-top:50px"></img>

This is a tool to create simple web apps using just Python.

- Usually, making websites requires HTML, CSS, JavaScript, but with Streamlit, you only write Python.

- It’s great for data apps because you can show charts, tables, and interactive dashboards in minutes.

- Imagine Excel on steroids—you change a few lines of code, and boom! A new dashboard appears.

https://1drv.ms/i/c/7f83dfb573ca445b/EQkOnzy0539CjvFs1_TgDRUBgEVNsk_WY5bUu2LucjAewQ?e=8jOPtW

### Logging in Python

Logging is like keeping a diary of what your program does. Instead of printing messages to the screen (which disappear), logging stores them in a file. This is super useful for debugging when something goes wrong.

- Think of it like a black box in an airplane—it records what happened before a crash!

- The logging library lets you save messages at different levels:

        DEBUG (tiny details, mostly for developers)

        INFO (general updates, like "User logged in")

        WARNING (something’s off but not a disaster)

        ERROR (something broke but the app is still running)

        CRITICAL (something broke so bad that everything stops)

## Features

- **Add Expenses**: Enter new expenses with details like date, amount, category, and notes.

- **View Expenses**: Retrieve and display expenses for a specific date.

- **Delete Expenses**: Remove unwanted expense records.

- **Expense Summary**: View a summary of expenses within a selected date range.

- **User-Friendly Interface**: Built with Streamlit for a clean and interactive UI.

## Tech Stack

- **Frontend**: Streamlit (Python-based UI framework)

- **Backend**: MySQL (Database) and Python (for API handling)

- **Libraries Used**:

      *mysql-connector-python* (Database interaction)

      *streamlit* (Frontend UI)

      *pandas* (Data handling)

      *logging* (For debugging and monitoring)

      *requests* (For API communication)

## Installation Guide

### Prerequisites

Ensure the following are installed:

- *Python* (version 3.8 or higher)

- MySQL Server

- Required Python libraries (install using           *requirements.txt*)

### Steps to Set Up

1. **Clone the repository**:

            git clone https://github.com/your-username/expense-manager.git
            cd expense-manager
2. **Install dependencies**:

            pip install -r requirements.txt
3. **Set up the MySQL database**:

-    Create a database named expense_manager.

-    Run the provided SQL script to create necessary tables.

4. Update the database credentials in .env or db_helpers.py.

5. **Start the application**:

          streamlit run app.py

## Database Structure

The application uses a single table expenses with the following structure:

            CREATE TABLE expenses (
                id INT AUTO_INCREMENT PRIMARY KEY,
                expense_date DATE NOT NULL,
                amount DECIMAL(10,2) NOT NULL,
                category VARCHAR(255) NOT NULL,
                notes TEXT
            );

## Future Enhancements

- *User Authentication*: Secure login system for multiple users.

- *Advanced Charts & Graphs*: Enhanced expense visualization.

- *Export Data*: Download expense reports in CSV/Excel format.

- *Mobile Optimization*: Better UI for small screens.

## Contributing

We welcome contributions! Feel free to fork this project, make improvements, and submit a pull request.

## Contact

For questions or suggestions, reach out via:

- Email: chnagabharath2003@gmail.com

- LinkedIn: https://www.linkedin.com/in/chamarthinagabharath/


