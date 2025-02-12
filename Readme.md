To-Do List Application

This is a simple To-Do List Application built using Python, Tkinter, and MongoDB. It provides functionalities to add, remove, and mark tasks as complete while storing them in a MongoDB database.

Features

Add tasks with Due Date and Priority

Remove selected tasks from the list

Mark tasks as completed

MongoDB integration for persistent storage

Scrollable task list for better usability

Prerequisites

Before running the application, ensure you have the following installed:

Python 3

MongoDB (Ensure MongoDB server is running locally or use a remote connection)

Required Python packages:

pip install pymongo tk

How to Run the Application

Clone this repository or download the todo_list.py script.

Ensure your MongoDB server is running.

Run the application using:

python todo_list.py

MongoDB Configuration

The application connects to a MongoDB instance running on localhost:27017. If you are using a remote MongoDB server, update the following line in todo_list.py:

client = MongoClient('mongodb://your-mongodb-url:27017/')

Usage Instructions

Enter a task along with its due date and priority.

Click Add Task to store it in the database.

Select a task from the list and click Mark as Complete to update its status.

Select a task and click Remove Task to delete it.

The list automatically refreshes after each action.

Screenshots

Coming Soon!

License

This project is licensed under the MIT License.

Author

Developed by Vaibhav Goyal

Contributions

Feel free to contribute by submitting issues or pull requests!
