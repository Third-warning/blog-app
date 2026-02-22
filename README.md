Blog App (MERN Stack)

A full-stack Blog Application built using:

React (Vite)
Node.js
Express.js
MongoDB
Tailwind CSS

This application allows users to create, read, update and delete blog posts with authentication.

How to Run This Project Locally
1️. Clone the Repository
git clone https://github.com/YOUR_USERNAME/blog-app.git
cd blog-app
2️. Install Dependencies
>Install Backend Dependencies
cd api
npm install
 >Install Frontend Dependencies
cd ../Client
npm install
3. Setup Environment Variables

Inside the api folder, create a file named:

.env

Add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Example for Local MongoDB:
MONGO_URI=mongodb://localhost:27017/blogapp

Make sure MongoDB is running on your system.

4️. Run the Backend Server

Inside api folder:

npm start

OR (if using nodemon):

npm run dev

Backend will start on:

http://localhost:5000
5️. Run the Frontend

Open a new terminal and go to:

cd Client
npm run dev

Vite will start the frontend at:

http://localhost:5173

Open this in your browser.

🛠 Project Structure
blogapp/
│
├── api/        → Backend (Node + Express + MongoDB)
├── Client/     → Frontend (React + Vite + Tailwind)
└── README.md
