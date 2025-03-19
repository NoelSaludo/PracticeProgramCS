# ToDo Console Application

This project is a simple console-based ToDo application designed to help you practice Object-Oriented Programming (OOP) concepts. The application allows users to manage their tasks by adding, viewing, and removing them.

## Description

The ToDo application is built using fundamental OOP principles. It includes classes that represent the core components of the application, such as tasks and the task manager. The application provides a command-line interface for users to interact with their task list.

## Classes

### Task
- **Description**: Represents a single task in the ToDo application.
- **Attributes**:
  - `id`: A unique identifier for the task.
  - `description`: A brief description of the task.
  - `isCompleted`: A boolean indicating whether the task is completed.

### TaskManager
- **Description**: Manages the collection of tasks.
- **Attributes**:
  - `tasks`: A list of `Task` objects.
- **Methods**:
  - `addTask(description)`: Adds a new task to the list.
  - `removeTask(id)`: Removes a task from the list by its ID.
  - `viewTasks()`: Displays all tasks with their status.
  - `markTaskAsCompleted(id)`: Marks a task as completed by its ID.

## Instructions

1. **Clone the Repository**: Clone the repository to your local machine.
2. **Navigate to the Project Directory**: Open a terminal and navigate to the `ToDoApp` directory.
3. **Compile the Application**: Compile the application using your preferred compiler.
4. **Run the Application**: Execute the compiled application to start managing your tasks.

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
Buy groceries task removed successfully!
```