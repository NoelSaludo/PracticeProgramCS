# ToDo Console Application

A client is asking you to create a simple ToDo application that
can help them list and organize tasks.
## Description

The ToDo application is built using fundamental functional programming principles.
It includes functions that represent the core components of the application, such as tasks and the task manager.
The application provides a command-line interface for users to interact with their task list.

## Functions

These functions form the backbone of the application. You can use this as the basis when writing the application.

### Task
- **Description**: Represents a single task in the ToDo application.
- **Attributes**:
  - `id`: A unique identifier for the task.
  - `description`: A brief description of the task.
  - `isCompleted`: A boolean indicating whether the task is completed.

### TaskManager Functions
- **Description**: Manages the collection of tasks.
- **Methods**:
  - `addTask(description)`: Adds a new task to the list.
  - `removeTask(id)`: Removes a task from the list by its ID.
  - `viewTasks()`: Displays all tasks with their status.
  - `markTaskAsCompleted(id)`: Marks a task as completed by its ID.

📌 **Note:** 
You can create other functions and modify current functions to handle features to your liking.


## Instructions

1. **Clone the Repository**: Clone the repository to your local machine.
2. **Navigate to the Project Directory**: Open a terminal and navigate to the `ToDoApp` directory.
3. **Write the Application**: Write the application using your preferred language.
4. **Run the Application**: Execute the compiled application to start managing your tasks.

## What to do
Write a simple ToDo application using functional paradigm in any preferred programming language. 
You can use the suggested functions as the basis when writing this program.

## Sample Application

When you run the application, you should see a menu with options to add, view, and remove tasks. Below is an example of what the application might look like:

### Main menu
```cmd
Welcome to the ToDo Application! Please choose an option:
1. Add a new task
2. View all task
3. Remove a task
4. Mark a task as completed
5. Exit

Enter your choice: 
```
### Adding a new task
```cmd
Enter task description: Buy Groceries
Enter tasked successfully!
```
### Viewing all task
```cmd
Current tasks:
1. Buy Groceries
Completed tasks:
1. AOOP assignement
```
### Removing a task
```cmd
What task to remove?
1. Current
2. Completed

Enter choice: 
```
#### Current task
```cmd
What task to remove:
1. Buy groceries

Enter choice: 1
Buy groceries task removed successfully!
```
#### Completed task
```cmd
What task to remove:
1. AOOP assignment

Enter choice: 1
AOOP assignment task removed successfully!
```
### Marking task as completed
```cmd
Mark task as complete:
1. Buy groceries
2. AOOP assignment

Enter choice: 2
AOOP assignment tasked completed!
```