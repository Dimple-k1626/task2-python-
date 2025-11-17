:

📝 To-Do List Application (Console-Based)

A simple and user-friendly command-line To-Do List application written in Python.
This program allows you to view, add, and remove tasks, with all data automatically saved in a tasks.txt file for future use.

🚀 Features

✔️ Add new tasks

✔️ View all saved tasks

✔️ Remove tasks by task number

✔️ Automatically saves tasks to tasks.txt

✔️ Loads tasks on startup

✔️ Simple and clean console interface

📂 Project Structure
.
├── to_do_list.py      # Main Python Program
└── tasks.txt          # Auto-created file that stores tasks

🛠️ How It Works
1. Loading Tasks

When the program starts, it reads existing tasks from tasks.txt.
If the file doesn’t exist, it creates a new empty list.

2. Saving Tasks

Every time a task is added or removed, the updated list is saved back to tasks.txt.

3. Menu Options

The user interacts through a looped menu:

1. View Tasks
2. Add Task
3. Remove Task
4. Exit

▶️ How to Run

Make sure Python is installed on your system.

Save the provided code as to_do_list.py.

Open a terminal and run:

python to_do_list.py


Start managing your tasks easily from the console!

📌 Example Usage
Adding a Task
Enter task to add: Buy groceries
Task added successfully!

Viewing Tasks
Your Tasks:
1. Buy groceries
2. Finish assignment

Removing a Task
Enter task number to remove: 1
Removed: Buy groceries

🗂️ File Handling

All tasks are stored in the file tasks.txt.

Created automatically if it doesn't already exist.

Ensures tasks remain available even after the program closes.

🧾 License

This project is free to use and modify
