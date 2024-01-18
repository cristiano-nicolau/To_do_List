# Todo List Web Application

This is a simple Todo List web application built using Flask and SQLAlchemy. Users can add tasks with optional tags, mark them as completed, and delete them. 

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have [Python](https://www.python.org/downloads/) installed on your machine.

### Installing Dependencies

Run the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```

## Run the app

Execute the following command to run the Flask application:
```bash
python3 main.py
```

### Usage
   - Visit http://127.0.0.1:5000/ in your browser.
   - Enter a task in the "Enter a task" input field.
   - Optionally, add tags separated by commas in the "Enter tags" input field.
   - Click the "Add" button to add the task to the list.
   - Mark tasks as completed by clicking the "[✓]" link.
   - Delete tasks by clicking the "[✗]" link.

## Project Structure

   - app.py: Main Flask application file.
   - templates/index.html: HTML template for the user interface.
   - requirements.txt: List of Python dependencies.

### Features

   - **Task Management:** Add, complete, and delete tasks.
   - **Tagging:** Optionally add tags to categorize tasks.

### Built With

   - **Flask:** - Web framework for Python.
   - **SQLAlchemy:** SQL toolkit and Object-Relational Mapping (ORM) library for Python.

