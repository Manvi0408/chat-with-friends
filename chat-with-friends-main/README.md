chat-With-Friends - A Real-Time Chat Application

chat-With-Friends is a real-time chat application built using the MERN (MongoDB, Express, React, Node.js) Stack. This project allows users to communicate seamlessly in a modern and responsive chat interface.

📌 Features

💬 Real-time messaging powered by WebSockets.

🔒 Secure authentication using JWT.

🎨 Modern UI with a responsive design.

🖼️ Profile avatars for a personalized experience.

🌐 Cloud-based database support with MongoDB.

🎥 Tutorial

Follow the complete tutorial here for step-by-step guidance.

📸 Screenshots

Login Page



Home Page



🚀 Installation Guide

Prerequisites

Before you begin, ensure you have the following installed:

Node.js (LTS recommended)

MongoDB (Ensure MongoDB is running before starting the server)

🔧 Installation

Method 1: Manual Setup

Clone the repository:

git clone (https://github.com/Aarnavanand/chat-with-friends)
cd chat-app-react-nodejs

Rename environment files from .env to .env:

cd public
mv .env.example .env
cd ../server
mv .env.example .env
cd ..

Install dependencies:

cd server
yarn install
cd ../public
yarn install

Start the application:

Frontend

cd public
yarn start

Backend (Open a new terminal and ensure MongoDB is running)

cd server
yarn start

🎉 Done! Open http://localhost:3000 in your browser.

Method 2: Docker Setup

This method requires Docker and Docker Compose installed.

Build the Docker images:

docker compose build --no-cache

Run the application:

docker compose up

🎉 Open http://localhost:3000 in your browser.

🛠️ Technologies Used

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Tokens)

Real-Time Communication: Socket.io

🤝 Contribution

We welcome contributions! To contribute:

Fork the repository.

Create a new feature branch.

Commit your changes.

Push your branch and create a pull request.

📜 License

This project is licensed under the MIT License.

✨ Created By

Aarnav Anand ✨

Crafted with ❤️ to enhance real-time communication experiences.

Happy Coding! 🚀

