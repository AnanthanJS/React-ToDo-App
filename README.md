**********React Todo App**********

A simple and interactive Todo App built with React that allows users to manage their tasks efficiently. This application supports full CRUD functionality—users can create, read, update, and delete tasks. Additionally, tasks are stored in the local storage so they persist even after the page is refreshed.

Features:
- **Add New Task**: Users can add a new task to their todo list.
- **Read Tasks**: View all the added tasks in a list format.
- **Update Task**: Edit or update an existing task's description.
- **Delete Task**: Remove a task from the list.
- **Persistent Data with Local Storage**: Tasks are saved in the browser’s local storage, ensuring data persists across sessions.
- **Responsive Design**: The app works seamlessly on both desktop and mobile devices.

Functionality In Progress:
- **Task Status Toggle**: The ability to mark a task as completed or incomplete is currently not implemented.

Installation:
To run the app locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/react-todo-app.git
   cd react-todo-app
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the development server**:

   ```bash
   npm start
   ```
   The app will be available at `http://localhost:3000/`.

Scripts:
- `npm start`: Starts the development server.
- `npm test`: Runs the test suite.
- `npm run build`: Builds the app for production.

Folder Structure:

react-todo-app/
│
├── public/
│   
│
├── src/
│   ├── components/       # Reusable components like TodoList, TodoItem, etc. 
│   	├── TodoCard.jsx            # For listing the tasks with edit and delete buttons
│   	├── TodoInput.jsx           # Contains the Input field & Add task button
│   	├── TodoList.jsx              # The List component that contains the TodoCard
│   ├── App.jsx            # Main app component
│   ├── index.css          # Main css for the app
│   ├── main.jsx          # Entry point for the app
│
├── index.html          # Main index page for rendering the root div.
├── package.json          # Project dependencies
└── README.md             # Project documentation

Technologies Used:

- **React**: A JavaScript library for building user interfaces.
- **CSS**: For styling the application.
- **React Hooks**: To manage state and lifecycle within functional components.
- **Local Storage**: For persisting tasks across browser sessions.

How to Use:
1. **Add a Task**: Use the input field to enter a task and click the 'Add' button to add it to the list.
2. **Update a Task**: Click on the 'Edit' button next to a task, modify the description, and add the task again.
3. **Delete a Task**: Click on the 'Delete' button to remove a task from the list.
4. **Persistent Tasks**: Refresh the page, and the tasks will still be available, thanks to local storage.

Future Enhancements:
- **Task Status Toggle**: Add the ability to toggle tasks between completed and incomplete states.
- **Task Filtering**: Add the ability to filter tasks by status (all, completed, incomplete).
- **Due Date Feature**: Add due dates to tasks and sort tasks accordingly.

Contributing:
Contributions are welcome! Please feel free to submit a pull request or open an issue for suggestions.

