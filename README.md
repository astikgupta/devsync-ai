
🚀 DevSync AI

DevSync AI is a full-stack, AI-powered developer collaboration platform designed to streamline communication, code discussions, and real-time collaboration among development teams. The platform combines modern frontend technologies with a scalable backend and real-time communication to provide a smooth and efficient developer experience.

✨ Key Features

💬 Real-time chat using WebSockets (Socket.IO)

🤖 AI-powered assistant to help developers with coding queries

🔐 Secure authentication and authorization

🌐 Fast and responsive frontend built with React + Vite

🛠 Robust backend with Node.js and Express

📡 RESTful APIs for frontend-backend communication

📁 Modular and scalable project architecture

⚡ Optimized for performance and future scalability

🧑‍💻 Tech Stack
Frontend

React (Vite)

JavaScript (ES6+)

HTML5

CSS3

Axios

Backend

Node.js

Express.js

Socket.IO

MongoDB

JWT Authentication

Tools & Platforms

Git & GitHub

Visual Studio Code

Postman

📂 Project Structure
devsync-ai/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
├── .vscode/
│   └── settings.json
│
├── .gitignore
├── README.md
└── package.json

⚙️ Installation & Setup
Prerequisites

Node.js (v18 or above)

npm or yarn

MongoDB (local or MongoDB Atlas)

1️⃣ Clone the Repository
git clone https://github.com/<your-username>/devsync-ai.git
cd devsync-ai

2️⃣ Backend Setup
cd backend
npm install
npm run dev


Create a .env file inside the backend folder:

PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


The frontend will run on:

http://localhost:5173


The backend will run on:

http://localhost:4000

🔐 Environment Variables
Variable	Description
PORT	Backend server port
MONGO_URI	MongoDB connection string
JWT_SECRET	JWT secret key
🚀 Future Enhancements

🧠 Advanced AI-powered chat features

📁 File and code snippet sharing

👥 Team-based workspaces

📊 Developer activity analytics

🌍 Deployment with CI/CD pipelines

📱 Mobile responsiveness improvements

🧪 API Testing

API endpoints can be tested using Postman

WebSocket events tested via browser or Socket.IO client

🤝 Contributing

Contributions are welcome and appreciated.

Steps to contribute:

Fork the repository

Create a new branch (feature/your-feature)

Commit your changes

Push to your fork

Open a Pull Request

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Astik Gupta

🎓 B.Tech CSE, Lovely Professional University

🌐 GitHub: https://github.com/astikgupta

⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub — it really helps!
