📇 Contact Manager MERN Application

A full-stack Contact Manager web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to manage contacts efficiently with complete CRUD functionality.

📖 Project Description

The Contact Manager MERN application is designed to help users store and manage contact information in an organized way. It provides a seamless interface to perform Create, Read, Update, and Delete (CRUD) operations.

The backend is developed using Node.js and Express.js, exposing RESTful APIs, while MongoDB is used as the database for storing contact details. The frontend is built with React.js, providing a dynamic and responsive user experience.

This project follows a modular and scalable architecture, making it easy to extend and maintain.

✨ Features

➕ Add new contacts

📋 View all contacts

✏️ Update existing contacts

❌ Delete contacts

🔄 RESTful API integration

📱 Responsive UI

🛠️ Tech Stack

Frontend:
React.js
HTML5, CSS3
Bootstrap (if used)
Backend:
Node.js
Express.js
Database:
MongoDB
Tools:
Git & GitHub
VS Code
Postman
📂 Project Structure
Contact-Manager-Mern/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/Sagargupta16/Contact-Manager-Mern.git
cd Contact-Manager-Mern
2️⃣ Install dependencies
Backend:
cd backend
npm install
Frontend:
cd frontend
npm install
3️⃣ Configure Environment Variables

Create a .env file inside the backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
4️⃣ Run the application
Start Backend:
cd backend
npm start
Start Frontend (new terminal):
cd frontend
npm start
