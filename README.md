<h1 align="center" id="title">Kanban Board Application</h1>

<p id="description">This project is a Kanban Board application developed using the MERN stack featuring JWT-based authentication for secure login and registration. The user interface is designed with Styled Components to provide a clean and responsive experience. The application allows users to dynamically create rename and delete columns on the board. Tasks can be added edited and removed with real-time updates reflected across the board. The drag-and-drop functionality enables seamless movement of tasks between columns to update their status. Additionally tasks can be assigned to users with assigned user names or avatars displayed on the task cards for easy identification. The application ensures an efficient and intuitive workflow management system for users.</p>

<h2>🚀 Demo</h2>

[https://kanban-client-orcin.vercel.app/](https://kanban-client-orcin.vercel.app/)

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   User Authentication: Secure login and registration using JWT with form validation and logout functionality.
*   Dynamic Columns: Ability to add rename and delete columns with a confirmation prompt for deletions.
*   Task Management: Create edit and delete tasks with details like title description and due date.
*   Drag-and-Drop: Seamless drag-and-drop functionality to move tasks between columns.
*   User Assignment: Assign tasks to users and display their avatars or names on task cards.
*   Responsive Design: Styled Components used for a clean modern and responsive user interface.
*   Real-Time Updates: Changes to tasks or columns reflect immediately across the board.
*   Interactive UI: Intuitive design for efficient workflow management.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the main repository</p>

```
git clone --recurse-submodules https://github.com/191prajjwal/Kanban-Board-.git  
```

<p>2. Navigate to the project folder</p>

```
cd Kanban-Board-  
```

<p>3. Navigate to the kanbanClient directory</p>

```
cd kanbanClient  
```

<p>4. Install the dependencies</p>

```
npm install
```

<p>5. Create a .env file in the kanbanClient directory and add your environment variables.</p>

```
VITE_API_BASE_URL=http://localhost:4000/api
```

<p>6. Start the development server</p>

```
npm run dev  
```

<p>7. Navigate to the kanbanSever directory</p>

```
cd ../kanbanSever  
```

<p>8. Create a .env file in the kanbanSever directory and add your environment variables.</p>

```
PORT=5000   MONGO_URI=your_mongodb_connection_string   JWT_SECRET=your_jwt_secret  
```

<p>9. Install the dependencies</p>

```
npm install
```

<p>10. Start the backend server</p>

```
npm run start
```

<h2>🍰 Contribution Guidelines:</h2>

We welcome contributions to improve this project! If you'd like to contribute please fork the repository make your changes and submit a pull request. Ensure that your code follows the existing style and is well-documented. For major changes please open an issue to discuss your ideas before implementation. Thank you for your interest in contributing!

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   MongoDB
*   Express.js
*   React.js
*   Node.js
*   ContextAPI
*   JWT
*   LocalStorage
*   JavaScript
*   Vercel

<h2>🛡️ License:</h2>

This project is licensed under the This project is licensed under the MIT License. You are free to use modify and distribute the code provided that proper credit is given to the original author.
