### TATool – MERN Stack TA Management Application

This is a full-stack TA management tool built using the **MERN stack (MongoDB, Express.js, React, Node.js)**. It enables seamless management of candidates, user authentication, and overall TA workflows.

---

### 🌐 Live Preview

- **Backend:** Runs locally at `http://127.0.0.1:5003`



## 🚀 Getting Started

### 🔹 Clone the Repository

git clone https://github.com/your-username/hrtool.git
cd 

🧩 Backend Setup
Step 1: Navigate to the backend folder

cd Candidex_BE

Step 2: Enter Npm Install

npm install

Step 3: Create a .env file in the server/ folder env

PORT=5003
REACT_APP_API_URL=http://127.0.0.1:5003
MONGO_URI=mongodb+srv://sravindra:oLgx02tlEyMIEo8q@cluster0.9gspz.mongodb.net/HRTool?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=your_jwt_secret
SESSION_SECRET=SECRET_SRC



Step 4: Start the backend server

npm run dev


🎨 Frontend Setup


Step 1: Navigate to the frontend folder

cd Candidex_FE

Step 2: Install dependencies

npm install

Step 3: Create a .env file in the client/ folder

VITE_API_URL=http://127.0.0.1:5003
VITE_SERVER_URL=http://127.0.0.1:5003


Step 4: Start the frontend development server

npm run dev



✅ Features
🔐 User Authentication (JWT-based)

📋 Candidate Data Entry and Tracking

📊 Dashboards and Candidate Status Views


👤 Role-based Access Control (Admin / TEam Leader / Team Member)


🧪 REST API with secure sessions


⚙️ Technologies Used
Frontend: React, Vite, TailwindCSS, Axios

Backend: Node.js, Express
Backend: Node.js, Express

Database: MongoDB with Mongoose

Authentication: JSON Web Tokens (JWT), Sessions

Deployment: Netlify (Frontend), Localhost (Backend)


🤝 Contributing

Fork the repository

Create a feature branch (git checkout -b feature-name)

Make your changes and commit them

Push to your branch (git push origin feature-name)

Open a Pull Request


👤 Author
Made with 💻 by Shiva Kumar Reddy &  Ravindra

📃 License
This project is licensed under the MIT License.








