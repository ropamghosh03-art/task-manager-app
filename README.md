📝 Task Manager App (Flutter)

📌 Overview

This is a Task Management mobile application built using Flutter as part of an assignment.
The app allows users to create, manage, and track tasks with a clean UI and smooth user experience.

---

🚀 Features

✅ Core Features

- Create, edit, and delete tasks (CRUD)
- Assign task status (Todo, In Progress, Done)
- Add task description
- Select due date using date picker
- Mark tasks as blocked by another task

---

🔍 Search & Filter

- Search tasks by title (with debouncing)
- Filter tasks by status

---

🔒 Blocking Logic

- Tasks can depend on other tasks
- A task remains blocked until the dependent task is completed
- Blocked tasks are visually disabled (greyed out)

---

💾 Local Storage

- Tasks are stored locally using SharedPreferences
- Data persists even after app restart

---

📝 Draft Saving

- While creating a task, input is automatically saved
- Draft is restored if user exits and comes back

---

⏳ Loading State

- Simulated API delay (2 seconds)
- Prevents duplicate submissions
- Shows loading indicator

---

🎨 UI/UX Enhancements

- Clean and minimal UI
- Responsive layout
- Styled task cards with shadows
- Empty state handling

---

🏗️ Tech Stack

- Flutter (Dart)
- SharedPreferences (local storage)

---

📱 How to Run

1. Clone the repository:

git clone <your-repo-link>

2. Navigate to project:

cd taskapp

3. Install dependencies:

flutter pub get

4. Run the app:

flutter run

👉 Choose Chrome or any available device

---

🎥 Demo

A short demo video is included showing:

- Task creation
- Editing & deletion
- Blocking logic
- Search & filter
- Draft recovery

---

🤖 AI Usage Disclosure

AI tools (ChatGPT) were used to:

- Understand requirements
- Improve code structure
- Debug issues
- Enhance UI/UX

All logic and implementation decisions were reviewed and understood before final submission.

---

📌 Notes

- The app is designed with a focus on usability and clean architecture
- Emphasis was placed on handling edge cases like blocking and draft saving
- Code is written in a modular and readable way for maintainability

---

🙌 Author

Developed by: Ropam Ghosh 

---
