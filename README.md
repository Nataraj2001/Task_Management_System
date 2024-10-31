# Task Management System 
The Task Management System is a web-based application designed to help users manage their tasks efficiently. With features like creating, updating, deleting, and tracking task status, this system provides a simple and effective solution for task management, perfect for individual or team productivity.

Backend_Api = https://vercel.com/api/toolbar/link/task-management-system-api-nine.vercel.app?via=project-dashboard-alias-list&p=1&page=/
Frontend =  https://task-management-system-ui3.vercel.app

## Features
User Authentication: Secure login and signup functionality to keep user data private.
Task CRUD Operations: Create, Read, Update, and Delete tasks with ease.
Status Tracking: Track the status of tasks (e.g., In Progress, Completed).
Task Prioritization: Set priorities for tasks to help users focus on the most critical items.
Responsive UI: Access the application on both desktop and mobile devices.
Notification Alerts: Receive alerts when tasks are due or status changes (optional).
Dark Mode Support: User preference settings for light or dark mode.
Technology Stack
Frontend: React.js, CSS, HTML, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Token (JWT)
Hosting : Vercel
## Installation
1. Clone the Repository
bash
git clone https://github.com/your-username/task-management-system.git
cd task-management-system
2. Backend Setup (Server)
Go to the server directory:
cd server

3.Install dependencies:
npm install
Create a .env file in the server directory and add the following variables:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

4.Start the backend server:
npm run dev
The backend server will run at http://localhost:8080.

5. Frontend Setup (Client)
Open a new terminal window, go to the client directory:
cd client
Install dependencies:
npm install
Start the frontend server:
npm start
The frontend will run at http://localhost:3000.

Running the Project
To run the entire project:

Start the backend server in one terminal window:

cd server
npm run dev
Start the frontend in another terminal window:
cd client
npm start
Open http://localhost:3000 in the browser to access the application

## API Endpoints
Endpoint	Method	Description
/api/tasks	GET	Get all tasks
/api/tasks	POST	Create a new task
/api/tasks/:id	PUT	Update a specific task
/api/tasks/:id	DELETE	Delete a specific task
/api/auth/register	POST	Register a new user
/api/auth/login	POST	User login
