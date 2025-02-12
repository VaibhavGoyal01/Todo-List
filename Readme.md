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
### Screenshots of Application
![Screenshot 2025-02-13 022252](https://github.com/user-attachments/assets/6899afe5-5817-4b6f-9bcc-05070fae09f1)
![Screenshot 2025-02-13 022445](https://github.com/user-attachments/assets/33169b76-7ba8-44f7-bed2-47a7c8221c0d)
![Screenshot 2025-02-13 022454](https://github.com/user-attachments/assets/ec74554a-2b41-47e4-b77b-a187da7d8e49)
![Screenshot 2025-02-13 022506](https://github.com/user-attachments/assets/15a518ec-b500-4d09-9ef6-a55b9b1fea47)



### Screenshots of MongoDB
![image](https://github.com/user-attachments/assets/c46da30a-7f16-4b79-bd8b-cc21ba47b80a)

### Video: 

https://github.com/user-attachments/assets/f94b0153-48f5-4165-8b55-568412e4d129


## Author

Developed by **Vaibhav Goyal**
