# 오픈소스SW응용
# TaskMaster

TaskMaster is a lightweight command-line task management tool designed to help users easily manage their daily tasks. This project is developed in Python and features a simple and intuitive command-line interface.

## Features

- Add, delete, and view tasks
- Manage task priorities
- Data persistence using JSON for storage
- Clean and straightforward command-line user interface

## Installation

1. **Clone the Repository**
   ---bash
   git clone https://github.com/kurosakiichig/TaskMaster.git

Navigate to the Project Directory
---bash
cd TaskMaster

Install Dependencies
---bash
pip install -r requirements.txt

Usage
Run the following command in the terminal to start TaskMaster:

bash
复制
python taskmaster.py
TaskMaster supports the following commands:

Add a task:

---bash
python taskmaster.py add "Task description" --priority 2
List tasks:

---bash
python taskmaster.py list
Remove a task:

---bash
python taskmaster.py remove 1

Contributing
Please refer to CONTRIBUTING.md for detailed guidelines on how to contribute.
