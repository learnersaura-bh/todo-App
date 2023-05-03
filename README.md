#React Todo List App
This is a simple Todo List app created with React, using the useState hook for state management and the uuid library for generating unique keys for list items.

#Features
Add new tasks to the list
Mark tasks as complete
Delete tasks from the list
Edit task descriptions
Filter tasks by completion status

#Technologies Used
-React
-React DOM
-uuid
-CSS
#Code Description
The main code file, App.js, contains the code for the Todo List app. It consists of a state variable list which holds the list of tasks and inputValue which holds the value of the input field for adding new tasks. The ToDoList component renders the list of tasks using the list state variable and a toggleButtonHandler function to handle completion of tasks. The buttonHandler function toggles the completion status of a task when the corresponding button is clicked. The addToList function adds a new task to the list state variable, and the handleKeyPress function handles the Enter key press event when adding a new task. The app also displays the number of completed and pending tasks, as well as a congratulatory message when all tasks have been completed.
