# JSL_Portfolio_Piece_OMPMAR491_BCL2401_Group1E_Omphemetse_Marole_JSL11

# Task Management Application

This is a task management application built using HTML, CSS, and JavaScript. The application allows users to create and manage tasks across different boards.

# Code Overview

The code is divided into several sections:

- Initialization: The application initializes by checking if local storage has data. If not, it loads initial data from the initialData array.
- DOM Elements: The code retrieves various DOM elements used in the application, such as navigation links, buttons, and input fields.
- Functions:
  - fetchAndDisplayBoardsAndTasks(): Retrieves tasks from local storage, extracts unique board names, and displays them in the navigation sidebar.
  - displayBoards(boards): Creates buttons for each board in the navigation sidebar.
  - filterAndDisplayTasksByBoard(boardName): Filters tasks by the selected board and displays them in the main content area.
  - refreshTasksUI(): Refreshes the task UI by re-filtering and re-displaying tasks.
  - styleActiveBoard(boardName): Styles the active board button.
  - addTaskToUI(task): Adds a new task to the UI.
  - setupEventListeners(): Sets up event listeners for various buttons and inputs.
  - toggleModal(show, modal): Toggles the visibility of the task modal window.
  - addTask(event): Handles the submission of the new task form.
  - toggleSidebar(show): Toggles the visibility of the sidebar.
  - toggleTheme()Toggles the light theme.
  - openEditTaskModal(task): Opens the edit task modal window.
  - saveTaskChanges(taskId): Saves changes to a task.
- Event Listeners: Various event listeners are set up to handle user interactions, such as clicking on buttons, submitting forms, and clicking outside the modal window.

# Usage

1. Open the application in a web browser.
2. Create new tasks by clicking the "Add New Task" button.
3. Edit existing tasks by clicking on them.
4. Filter tasks by board using the navigation sidebar.
5. Toggle the light theme using the theme switch.
6. Toggle the sidebar using the sidebar button.

# Challenges

1. When changing the theme to light the logo doesn't disapear.
2. Was struggling to move the toggle theme side-bar-bottom but i managed to fix it.
3. I was struggling with Add New Task and the Create Task but managed to fix.
   <<<<<<< HEAD
4. https://www.loom.com/share/f5f947fc482a42a89cbac9fe7ee8eee1?sid=568b181f-77d1-4555-a0a2-6cd0295654a2
5. https://www.loom.com/share/99e3859e8ae44e26b3424430b52526bc?sid=af97fdf2-e591-4bf4-9945-c632222c5bb0
