# To-Do List Manager

This is a simple command-line To-Do List Manager implemented in C. It allows users to add tasks, remove tasks, view tasks, mark tasks as completed, and exit the application.

## Features

- Add tasks: Users can add tasks to the to-do list by entering task text.
- Remove tasks: Tasks can be removed from the list by specifying the task ID.
- View tasks: All tasks in the list are displayed, with options to sort them by task text or task ID.
- Mark completion: Users can mark tasks as completed by providing the task ID.
- Error handling: The program includes error handling for invalid user inputs.
- Input buffer clearing: Input buffer is cleared to ensure correct behavior when reading user input.
- Maximum task limit: The program assumes a maximum of 100 tasks.
- Efficient task removal: Tasks are efficiently removed by shifting positions in the array.
- Clear output: Informative output messages guide the user through each action.
- Standard library usage: Standard C libraries are utilized for input/output operations, memory management, etc.
- Quicksort implementation: Sorting is implemented using the `qsort()` function.
- Modular design: Functionalities are separated into distinct functions for organization and ease of modification.
- User-friendly interface: Clear instructions and a concise menu make the interface user-friendly.
- Encapsulation: Task attributes are encapsulated within a structure.
- Scalability: The program can be extended by implementing dynamic memory allocation.

## Usage

1. Compile the code using a C compiler.
2. Run the compiled executable.
3. Follow the on-screen instructions to manage tasks:
   - Choose options from the menu to add, remove, view, or mark tasks as completed.
   - Tasks can be sorted by task text or task ID for viewing.

