## Personal To-Do List Manager Programming Exercise

Problem Statement: Create a simple To-Do List Manager where users can add tasks, mark them as completed, and delete them. The user should also have the
option to view all tasks or filter them based on their completion status.

Functional Requirements:
1. Enable users to add new tasks with a description and due date.
2. Allow tasks to be marked as 'completed'.
3. Provide an option to delete tasks.
4. Implement the ability to view tasks, either all at once or filtered by 'completed' or 'pending'.

Key Focus:
1. Behavioral Pattern: Use the Memento Pattern to allow the user to undo or redo actions.
2. Creational Pattern: Use the Builder Pattern for constructing tasks with optional attributes like due date or tags.
3. OOP: Focus on encapsulation by keeping task data and methods together in a class.

Possible Inputs:
1. Add Task: "Buy groceries, Due: 2023-09-20"
2. Mark Completed: "Buy groceries"
3. View Tasks: "Show all", "Show completed", "Show pending"

Possible Outputs;
Task List: Display the tasks along with their status, for example, "Buy groceries - Completed, Due: 2023-09-20"
