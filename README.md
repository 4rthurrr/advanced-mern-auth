# Advanced MERN Authentication System

Welcome to the **Advanced MERN Authentication System**! This project is a secure and scalable authentication system built using the **MERN stack** (MongoDB, Express, React, and Node.js). It provides a robust solution for handling user authentication and authorization in modern web applications.

---

## ✨ Key Features

### **User Authentication**
- **User Registration and Login**: Users can securely register and log in using their email and password.
- **JWT-Based Session Management**: Secure authentication using JSON Web Tokens (JWT) for session management.

### **Password Management**
- **Password Hashing**: Passwords are securely hashed using **bcryptjs** before being stored in the database.
- **Password Reset**: Users can reset their passwords via email using **Mailtrap** for testing.

### **Access Control**
- **Protected Routes**: Middleware ensures that only authenticated users can access specific endpoints.
- **Role-Based Access Control (RBAC)**: Different levels of access are granted based on user roles (e.g., admin, user).

### **Environment Configuration**
- **Environment Variables**: Sensitive data like database URI, JWT secret, and Mailtrap credentials are securely managed using **dotenv**.

### **Frontend Integration**
- **React Frontend**: Built with React for a dynamic and responsive user interface.
- **State Management**: Uses **zustand** for efficient state management.
- **Routing**: Handled by **react-router-dom** for seamless navigation.
- **Styling**: UI components are styled using **Tailwind CSS** for a modern and clean design.
- **API Requests**: Handled using **axios** for smooth communication with the backend.

### **Development Tools**
- **ESLint**: Ensures clean and consistent code with linting.
- **Nodemon**: Automatically restarts the server during development.
- **Vite**: Powers the frontend with fast development and build times.

---

## 🚀 Project Structure

### **Backend**
- Built with **Express.js**.
- **MongoDB** for database storage.
- **JWT** for secure authentication.
- Environment variables managed using **dotenv**.

### **Frontend**
- Built with **React**.
- State management handled by **zustand**.
- Routing managed by **react-router-dom**.
- Styled with **Tailwind CSS**.
- API requests handled using **axios**.

---

## 🛠️ Getting Started


### Setup .env file

```bash
MONGO_URI=your_mongo_uri
PORT=5000
JWT_SECRET=your_secret_key
NODE_ENV=development

MAILTRAP_TOKEN=your_mailtrap_token
MAILTRAP_ENDPOINT=https://send.api.mailtrap.io/

CLIENT_URL= http://localhost:5173
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```

### I'll see you in the next one! 🚀
