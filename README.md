# AI Task Manager with Smart Suggestions

## Description
The AI Task Manager is a task management application designed to help users efficiently manage their tasks. With the added power of AI, the app suggests task priorities based on the task descriptions provided by the user. It simplifies organizing tasks and ensures you focus on what matters most.

---

## Features

### 1. Task Management (CRUD Operations)
- **Add Tasks:** Add new tasks with a description (e.g., "Finish homework," "Buy groceries").
- **View Tasks:** View all tasks in a structured task list.
- **Edit Tasks:** Modify task descriptions if plans or priorities change.
- **Delete Tasks:** Remove tasks once completed.

### 2. AI-Based Task Prioritization
- The AI analyzes the task description and assigns one of the following priorities:
  - **High Priority:** Urgent or critical tasks, e.g., tasks with deadlines.
  - **Medium Priority:** Important tasks that can wait.
  - **Low Priority:** Non-urgent tasks that can be done later.

### 3. User Interface (UI) Enhancements
- Tasks are displayed in order of priority for better visualization.
- Each priority is clearly indicated using color-coded labels:
  - **High Priority:** Red
  - **Medium Priority:** Yellow
  - **Low Priority:** Green
- Users can manually reorder tasks if needed.

---

## Folder Structure
```
AI-TaskManager/
├── index.html       # Home page of the application
├── task.html        # Task management interface
├── imageForTask.png # Visual assets for the application
└── README.md        # Documentation for the project
```

---

## How It Works
1. **Adding Tasks:** Users input a task description in the provided text field and click the "Add Task" button.
2. **AI Prioritization:** The app analyzes the description and suggests a priority level.
3. **Viewing and Editing:** Tasks appear in a list with priority labels. Users can edit or reorder tasks as needed.
4. **Completing Tasks:** Users can mark tasks as completed or delete them entirely.

---

## Evaluation Criteria

### 1. CRUD Operations
- Ensure all task operations (Create, Read, Update, Delete) work flawlessly and in real-time.

### 2. AI Suggestions
- AI provides logical priority labels based on task descriptions.
- Tasks with deadlines or urgency should be labeled as **High Priority**.

### 3. User Interface (UI)
- Tasks are displayed in an intuitive layout, ordered by priority.
- Color-coded labels make it easy to identify priorities.
- Users can interact with the task list effortlessly.

---

## Technologies Used
- **HTML**: For structuring the app.
- **CSS**: For styling and UI.
- **JavaScript**: For functionality and AI prioritization.

---

## Future Improvements
- Add task categories (e.g., Work, Personal, Shopping).
- Implement due dates and reminders.
- Enable synchronization with cloud storage for task backups.
- Integrate more advanced AI suggestions using external APIs.

---


## Credits
This project was developed by Chhiteshwari. Special thanks to Navgurukul for their guidance and support.

