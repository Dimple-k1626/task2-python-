# To-Do List Application

A simple console-based To-Do List application written in Python.\
It allows users to **view**, **add**, and **remove** tasks, with all
tasks saved to a text file.

------------------------------------------------------------------------

## 📌 Features

-   Load tasks from a file
-   Save tasks automatically after changes
-   View all existing tasks
-   Add a new task
-   Remove a task by number
-   Simple text‑based interface

------------------------------------------------------------------------

## 📁 File Structure

    tasks.txt       # Stores all tasks
    main.py         # Application source code

------------------------------------------------------------------------

## ▶️ How to Run

1.  Ensure Python 3 is installed.
2.  Place `main.py` in your project folder.
3.  Run the application:

``` bash
python main.py
```

------------------------------------------------------------------------

## 🧩 Code Overview

### Loading Tasks

``` python
def load_tasks():
    try:
        with open(TASK_FILE, "r") as file:
            return [task.strip() for task in file.readlines()]
    except FileNotFoundError:
        return []
```

### Saving Tasks

``` python
def save_tasks(tasks):
    with open(TASK_FILE, "w") as file:
        for task in tasks:
            file.write(task + "\n")
```

### Adding & Removing Tasks

Users can add tasks via input and remove them by selecting their number.

------------------------------------------------------------------------

## 📜 License

This project is free to use and modify.
