## TaskForge – Console-Based Task Manager

# Objective:
Build a fully functional terminal-based Task Manager in Python using Object-Oriented Programming. The user can add, update, delete, filter, and persist tasks (to file), mimicking a real-life todo application — but focused entirely on core Python skills like classes, logic, file I/O, and control flow.

# Key Features:
Add a new task with title, priority, due date, and status


View all tasks or filter by status or due date


Mark a task as complete


Edit task details


Delete a task


Save/load task data to/from a file (tasks.json)



# Modules & Class Design:
1. Task class

Attributes:
- id (auto-generated)
- title
- priority (Low, Medium, High)
- due_date
- status (Pending, Completed)

Methods:
- to_dict()
- from_dict()


2. TaskManager class

Attributes:
- task_list (List of Task objects)

Methods:
- add_task()
- view_tasks()
- update_task()
- mark_complete()
- delete_task()
- filter_tasks(by='status' or 'due_date')
- save_to_file()
- load_from_file()


Tasks to Implement:
1. Add Task
Take user input (title, priority, due_date)


Generate unique ID


Store in task_list




2. Update Task
Search by ID


Update fields interactively


3. Mark as Complete
Set status of task to Completed


4. Delete Task
Remove task by ID


5. View Tasks
Print tasks in formatted table


Options: View All, Filter by Status (Pending/Completed), Filter by Due Date (Today or this week)


6. Save & Load
Save task list to tasks.json


# Load on app start Evaluation Points:
  Proper class structure (Task, TaskManager)
  
  
  Use of encapsulation and object methods
  
  
  Unique task ID generation
  
  
  Input validation and error handling


Filtering logic (by status, due date)


File I/O using JSON
