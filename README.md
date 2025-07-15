📝 To-Do List App
A simple and interactive to-do list application built using React. It allows users to add, mark as complete, and delete tasks, with persistent local storage support.

🚀 Features
✅ Add new tasks
🔁 Toggle task completion (strike-through effect)
❌ Delete tasks
💾 Stores data in localStorage so tasks are saved across browser sessions
⚛️ Built with React Hooks (useState, useEffect, useRef)

🛠️ How It Works
Todo.jsx:

* Main component that holds the list and input field.
* Handles task addition and storage updates.
* Loads tasks from localStorage on first render.

TodoItems.jsx:

* Renders each task with buttons to mark complete or delete.
* Updates localStorage and triggers state updates accordingly.

💡 How to Run
Clone the repository:
git clone https://github.com/Sutarsiddhi/todo-list-app.git
cd todo-list-app

Install dependencies:
npm install

Start the development server:
npm run dev

🧠 Concepts Used
* React functional components
* useState, useEffect, useRef
* JSON storage with localStorage
* Conditional rendering
* CSS styling for strike-through and hover effects

📌 Future Improvements
* Task edit feature
* Due date or priority tags
* Dark mode
* Backend storage with MongoDB or Firebase













# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
