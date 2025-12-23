Real-Time Chat Application (MERN Stack + WebSocket)

This is a Real-Time Chat Application developed using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and WebSocket (Socket.IO).
The application allows users to communicate with each other instantly through real-time messaging.

Image
<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/624b9864-83e6-4624-a301-f84f26084078" />


✨ Features

User Registration and Login

Real-time messaging using WebSocket

One-to-One Chat

Online user support

Secure authentication using JWT

Responsive user interface

🛠️ Technologies Used
Frontend

React.js

Socket.IO Client

Axios

HTML, CSS, JavaScript

Backend

Node.js

Express.js

MongoDB

Mongoose

Socket.IO

JSON Web Token (JWT)

bcrypt.js

📁 Project Structure
Real-Time-Chat-App/
│
├── client/          # React Frontend
│   └── src/
│
├── server/          # Node.js Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
└── README.md

⚙️ Installation and Setup
Step 1: Clone the Repository
git clone https://github.com/your-username/my-chat-app.git
cd my-chat-app

Step 2: Backend Setup
cd server
npm install


Create a .env file inside the server folder:

PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


Start the backend server:

npm start

Step 3: Frontend Setup
cd client
npm install
npm run dev


Frontend will run on:

http://localhost:3000


Backend will run on:

http://localhost:8000

🔌 Real-Time Communication (WebSocket)

Socket.IO is used for real-time, bidirectional communication

Messages are delivered instantly without refreshing the page

WebSocket ensures fast and efficient data transfer

🔐 Authentication

JWT is used for secure user authentication

Passwords are encrypted using bcrypt

Protected routes can only be accessed by authenticated users

🚀 Future Enhancements

Group Chat

Typing Indicator

Message Read Receipts

Online/Offline Status

📄 Conclusion

This project demonstrates the implementation of real-time communication using the MERN stack and WebSocket technology.
It is suitable for academic projects and learning purposes.
