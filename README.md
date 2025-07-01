# Task-6-GUI-based-To-do-app
## Features
- Add task
- Delete task
- Task list view
- GUI interface
- Real time interactivity
## Classes
- ToDoApp
Main GUI class extending JFrame, contains all logic and UI elements
## Objects
- JTextField taskInput
For entering new tasks
- JButton addButton
For adding the typed task
- JButton deleteButton
For deleting selected task
- DefaultListModel<String> taskListModel
Stores task data dynamically
- JList<String> taskList
Displays list of task to the user
- JScrollPane scrollPane
Adds scroolable functionality to the task list
## Libraries and Packages used
- javax.swing.*
Used for GUI components like JFrame, JButton, JTextField,etc
- java.awt.*
For layout managers like BorderLayout
- java.awt.event.*
For handling button click events
- java.util.*
Used for dynamic data structures if needed later
## Explnation
- JFrame
The main window for the app
- Task input and add button
User types a task in the text field
Clicks add to insert it into the list
- Task List
stores all tasks
shows the tasks
add scroll
- Add button
Tasks the input
Adds it to list
Clears the input field
- Delete Button
Gets the selected index from list
Selected one gets removed
  

