# Task-Management-App
A simple Python-based task management application that allows users to add, remove, list, and recommend tasks based on their priority.
The application uses machine learning to recommend high-priority tasks.

## Features

- Add tasks with priority levels (Low, Medium, High).

- Remove tasks by description.

- List all tasks.

- Recommend high-priority tasks using a machine learning model.

- Tasks are stored persistently in a CSV file.

## Prerequisites
**Python:**
Ensure Python 3.x is installed on your system.

**Required Python Packages:**

`pandas==1.3.3`

`scikit-learn==0.24.2`


## File Structure

**main.py:** Main application script.

**tasks.csv**: CSV file for storing tasks (auto-generated).

**README.md**: Instructions and details about the project.

## Example Interaction
```
Task Management App
1. Add Task
2. Remove Task
3. List Tasks
4. Recommend Task
5. Exit


Select an option: 1
Enter task description: Complete assignment
Enter task priority (Low/Medium/High): High
Task added successfully.

Select an option: 4
Recommended task: Complete assignment - Priority: High

Select an option: 5
Goodbye!
```

## Notes

Tasks with higher priorities are recommended first.

Ensure the tasks.csv file is in the same directory as main.py.


## Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests.
