# CODSOFT_TASK_01
This Python script implements a command-line to-do list application. Here's a brief theoretical explanation of its components and functionality:TodoList Class,main Function,Entry Point Check

Certainly! Here's a theoretical explanation of the code for a simple command-line to-do list application:

### Overview
The script is designed to manage a to-do list through a command-line interface. It allows users to add tasks, view the list of tasks, and delete tasks by their number. The core functionality is encapsulated in a class, and user interactions are handled in a main function.

### Key Components

1. **TodoList Class**
   - **Initialization**: When an instance of the `TodoList` class is created, it initializes an empty list to store tasks.
   - **Add Task Method**: This method takes a task description as input and adds it to the list of tasks. It also prints a confirmation message indicating that the task has been added.
   - **View Tasks Method**: This method checks if there are any tasks in the list. If the list is empty, it informs the user that there are no tasks. If there are tasks, it prints each task along with its number in the list.
   - **Delete Task Method**: This method takes a task number as input, checks if it is valid (i.e., within the range of the list), and removes the corresponding task. If the number is invalid, it prints an error message. Upon successful deletion, it prints a confirmation message.

2. **Main Function**
   - **Initialization**: An instance of the `TodoList` class is created to manage the tasks.
   - **Infinite Loop for User Interaction**: The function runs an infinite loop that repeatedly presents a menu of options to the user: add a task, view tasks, delete a task, or exit the program.
     - **Add Task**: When the user chooses to add a task, they are prompted to enter the task description, which is then added to the list.
     - **View Tasks**: When the user chooses to view tasks, the function calls the method to display all tasks.
     - **Delete Task**: When the user chooses to delete a task, they are prompted to enter the task number. The function validates the input and deletes the specified task if the input is valid.
     - **Exit**: When the user chooses to exit, the loop terminates, and the program ends.
     - **Invalid Choice Handling**: If the user enters an invalid option, the program informs them and prompts again.

3. **Entry Point Check**
   - This check ensures that the main function runs only when the script is executed directly. If the script is imported as a module in another script, the main function will not run automatically.

### Execution Flow
- The script starts by creating an instance of the `TodoList` class.
- It enters an infinite loop, presenting the user with a menu of options.
- Depending on the user's choice, it either adds a task, views tasks, deletes a task, or exits the program.
- User inputs are handled with appropriate checks to ensure valid operations.
- The program runs until the user chooses to exit, at which point it terminates gracefully.

This structure provides a simple yet functional command-line interface for managing a to-do list, demonstrating basic principles of object-oriented programming and user input handling in Python.
