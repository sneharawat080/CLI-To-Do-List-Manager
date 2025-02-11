# CLI To-Do List Manager

## Overview
The CLI To-Do List Manager is a simple command-line tool built using Python that allows users to manage their tasks efficiently. It provides functionalities such as adding, listing, updating, deleting, and marking tasks as done.

## Features
- **Add a Task:** Add a new task to the list.
- **List Tasks:** Display all tasks with their status.
- **Update a Task:** Modify an existing task's description.
- **Delete a Task:** Remove a task from the list.
- **Mark Task as Done:** Mark a task as completed.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cli-todo-manager.git
   ```
2. Navigate to the project directory:
   ```sh
   cd cli-todo-manager
   ```
3. Ensure you have Python installed (Python 3 recommended).

## Usage
Run the script using Python and pass the appropriate command:

### Add a Task
```sh
python todo.py add "Buy groceries"
```

### List All Tasks
```sh
python todo.py list
```

### Update a Task
```sh
python todo.py update 1 "Buy groceries and cook dinner"
```

### Delete a Task
```sh
python todo.py delete 1
```

### Mark Task as Done
```sh
python todo.py done 1
```

## Dependencies
- Python (>=3.6)
- No external libraries required (uses built-in `argparse` and `json` modules)

## Contributing
Feel free to fork the repository and submit pull requests with improvements or new features.

## License
This project is licensed under the MIT License.

