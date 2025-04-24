
---

## TA Tool – MERN Stack TA Management Application

This is a full-stack TA management tool built using the **MERN stack (MongoDB, Express.js, React, Node.js)**. It enables seamless management of candidates, user authentication, and overall TA workflows.

---

## 🌐 Live Preview

- **Backend:** Runs locally at `http://127.0.0.1:5003`

---

## 🚀 Getting Started

### 🔹 Clone the Repository

```bash
git clone https://github.com/katreddy-bit/candidex.gitgit clone https://github.com/katreddy-bit/candidex.git
cd candidex
```

### 🧩 Backend Setup

1. Navigate to the backend folder:

    ```bash
    cd Candidex_BE
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `server/` folder:

    ```
    PORT=5003
    REACT_APP_API_URL=http://127.0.0.1:5003
    MONGO_URI=mongodb+srv://sravindra:oLgx02tlEyMIEo8q@cluster0.9gspz.mongodb.net/HRTool?retryWrites=true&w=majority&appName=Cluster0
    JWT_SECRET=your_jwt_secret
    SESSION_SECRET=SECRET_SRC
    ```

4. Start the backend server:

    ```bash
    npm run dev
    ```

---

### 🎨 Frontend Setup

1. Navigate to the frontend folder:

    ```bash
    cd Candidex_FE
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the `client/` folder:

    ```
    VITE_API_URL=http://127.0.0.1:5003
    VITE_SERVER_URL=http://127.0.0.1:5003
    ```

4. Start the frontend development server:

    ```bash
    npm run dev
    ```

---

## ✅ Features

- 🔐 **User Authentication** (JWT-based)
- 📋 **Candidate Data Entry and Tracking**
- 📊 **Dashboards and Candidate Status Views**
- 👤 **Role-based Access Control** (Admin / Team Leader / Team Member)
- 🧪 **REST API with secure sessions**

---

## ⚙️ Technologies Used

- **Frontend:** React, Vite, TailwindCSS, Axios
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose
- **Authentication:** JSON Web Tokens (JWT), Sessions
- **Deployment:** Netlify (Frontend), Localhost (Backend)

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch:

    ```bash
    git checkout -b feature-name
    ```

3. Make your changes and commit them
4. Push to your branch:

    ```bash
    git push origin feature-name
    ```

5. Open a Pull Request

---

## 👤 Author

Made with 💻 by Shiva Kumar Reddy & Ravindra

---

## 📃 License

This project is licensed under the MIT License.

---
