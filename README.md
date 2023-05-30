# Task-Master
This Flask application is a simple to-do list manager that allows users to perform CRUD operations. The app utilizes a SQLite database to store the tasks and their associated information.


The main features of the application include:

* Create Task: Users can enter a task in the provided input field and submit it. The task is then added to the database and displayed in the task list.
* View Tasks: The application displays all the tasks stored in the database in chronological order, with the most recently created tasks appearing at the top.
* Update Task: Users can click on the "Update" button next to a task to edit its content. The updated task is then saved to the database, and the task list is refreshed.
* Delete Task: Users can click on the "Delete" button next to a task to remove it from the list and the database.

The application uses Flask, a Python web framework, for handling HTTP requests and rendering HTML templates. It also utilizes Flask-SQLAlchemy, an extension that simplifies working with databases in Flask applications.

Overall, this Flask app provides a basic and intuitive interface for managing tasks, making it easier for users to keep track of their to-do lists.