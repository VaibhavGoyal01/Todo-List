# To-Do List Application

A simple To-Do List Application built using Python, Tkinter, and MongoDB. This application allows users to add, remove, and mark tasks as complete while storing them in a MongoDB database for persistent storage.

## Features

- Add tasks with Due Date and Priority
- Remove selected tasks from the list
- Mark tasks as completed
- MongoDB integration for persistent storage
- Scrollable task list for better usability

## Prerequisites

Before running the application, ensure you have the following installed:

- **Python 3**
- **MongoDB** (Ensure MongoDB server is running locally or use a remote connection)
- Required Python packages:

  ```sh
  pip install pymongo tk
  ```

## How to Run the Application

1. Clone this repository or download the `main.py` script.
2. Ensure your MongoDB server is running.
3. Run the application using:

   ```sh
   python todo_list.py
   ```

## MongoDB Configuration

The application connects to a MongoDB instance running on `localhost:27017`. If you are using a remote MongoDB server, update the following line in `main.py`:

```python
client = MongoClient('mongodb://your-mongodb-url:27017/')
```

## Usage Instructions

1. Enter a task along with its due date and priority.
2. Click **Add Task** to store it in the database.
3. Select a task from the list and click **Mark as Complete** to update its status.
4. Select a task and click **Remove Task** to delete it.
5. The list automatically refreshes after each action.

## Screenshots

![Screenshot 2025-02-13 022506](https://github.com/user-attachments/assets/4c54fba1-89e5-498a-8e02-2a6c9900a0c4)


## Author

Developed by **Vaibhav Goyal**
