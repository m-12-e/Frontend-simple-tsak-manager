Simple Task Manager (Frontend - HTML, CSS, JavaScript)
This is a straightforward web-based task manager application built using only plain HTML, CSS, and JavaScript. It provides a clean and responsive user interface where you can manage your tasks directly in the browser, without any backend server.

##Features
View Tasks: See a list of your tasks, showing their title and completion status.
Add New Task: Easily add new tasks to your list using an input field.
Mark as Completed: Toggle the completion status of any task. Completed tasks are visually distinct (e.g., strike-through text, different background color).
Delete Task: Remove tasks you no longer need from the list.
Input Validation: Prevents you from adding tasks with empty titles.
Task Filtering: Filter tasks to display "All," "Active" (uncompleted), or "Completed" tasks.

##Technologies Used
HTML5: For structuring the content of the web page.
CSS3: For styling the application, creating a modern and responsive design. This includes custom variables for easy theming and responsive adjustments.
JavaScript (ES6+): For all the interactive logic, including task management, DOM manipulation, event handling, validation, and filtering.
Google Fonts (Inter): For a clean and readable typeface.
Font Awesome: For scalable vector icons (check, undo, trash).

##Usage
Add a Task: Type your task into the "Add a new task..." input field and press Enter or click the "Add Task" button.
Mark Complete/Pending: Click the green checkmark (or yellow undo arrow) button next to a task to toggle its completion status.
Delete a Task: Click the red trash can icon next to a task to remove it from the list.
Filter Tasks: Use the "All," "Active," and "Completed" buttons above the task list to filter what tasks are displayed.
Hardcoded Data
For simplicity and to meet the challenge guidelines (no backend needed), the task data is stored in a JavaScript array directly within the HTML file. This means any tasks you add, complete, or delete will not persist if you close and reopen the browser tab or refresh the page.

let tasks=[
        {id:1,  title:'Buy groceries',  completed: false },
        {id:1,  title:'Read a book',  completed: true },
        {id:1,  title:'Walk the dog',  completed: false },
    ];

If you were to expand this into a production application, you would typically integrate a backend API or use browser's local storage for data persistence.
