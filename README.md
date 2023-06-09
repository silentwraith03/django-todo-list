## Project Overview
TodoApp is a simple web application built with Django that allows you to manage your tasks and to-do lists.
## Features
- Create, update, and delete tasks
- Mark tasks as completed
- Filter tasks by status and due date
- Search for specific tasks
- Responsive design for mobile and desktop

## Screenshots
<img src='images/sc1.png'>
<img src='images/sc2.png'>
<img src='images/sc3.png'>

## Prerequisites
Before running the polls website, make sure you have the following installed:

* Python (version 3.6 or later)
* Django (version 3.0 or later)

## Setup Instructions

1. Navigate into the project directory.
2. Create a virtual environment in a `venv/` folder by typing `python -m venv venv` in your console.
3. Activate the venv using `source venv/bin/activate` (Linux, MacOS) or `venv\Scripts\activate.bat` (Windows).
4. Install the dependencies with `python -m pip install -r requirements.txt`
5. Generate the empty SQLite database and tables using `python manage.py migrate`
5. Run the app with `python manage.py runserver`
6. Browse to the [app home page](http://localhost:8000/) to see the list of todo lists, which will initially be empty. 

You can now start using the UI to add your to-do lists and to-do items to the database. The data will be stored in a new `db.sqlite3` file in the root of your project directory.

You can also use Django's auto-generated [admin interface](http://localhost:8000/admin/) to view, add, and edit the data.

## Project Structure
```arduino
django-todo-list/
  |- images/
  |- todo_app/
  |- todo_project/
  |- db.sqlite3/
  |- manage.py/
  |- LICENSE/
  |- README.md/
  |- requirement.txt/
```

## Tech Stack
* Django
* Django REST Framework
* HTML
* CSS
* JavaScript

## License
[MIT](LICENSE)

