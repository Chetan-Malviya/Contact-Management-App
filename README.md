# 📇 Contact Management App (Node.js + Express + MongoDB + JWT)

A complete **Contact Manager Backend Application** built using **Node.js**, **Express.js**, **MongoDB**, and **JWT Authentication**.  
This project demonstrates how to design and develop a scalable RESTful API with authentication, validation, and CRUD functionality.

---

## 🚀 Features

- 🔐 User Registration and Login (JWT Authentication)
- 🧾 Full CRUD operations for managing contacts
- 🧑‍🤝‍🧑 User-specific contact management
- ⚙️ RESTful API design with Express
- 🔒 Secure password hashing with bcrypt
- 🧩 Input validation and error handling
- 🌍 Environment variable configuration using dotenv
- 🪵 Clean and modular code structure

---

## 🛠️ Tech Stack

| Technology | Description |
|-------------|-------------|
| **Node.js** | JavaScript runtime environment |
| **Express.js** | Web framework for building REST APIs |
| **MongoDB** | NoSQL database for storing data |
| **Mongoose** | MongoDB object modeling tool |
| **JWT (JSON Web Token)** | Authentication mechanism |
| **bcryptjs** | Library for password hashing |
| **dotenv** | For managing environment variables |

---

## 📁 Project Structure

contact-management-app/

│

├── config/ # Database connection setup

├── controllers/ # Route controller logic

├── middleware/ # Authentication and error handling

├── models/ # Mongoose schemas (User, Contact)

├── routes/ # Express routes for users & contacts

├── .env.example # Example environment variables

├── server.js # Entry point of the app

└── package.json # Project metadata and dependencies

---

## 🧪 Testing the API

- You can test the routes using:

- Postman

- Thunder Client (VS Code Extension)

Example:

- Add Authorization header: Bearer <your_jwt_token>

- Use JSON body for POST/PUT requests

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Chetan-Malviya/Contact-Management-App.git
cd Contact-Management-App
```

### 2️⃣ Install dependencies
```bash
npm install
```

3️⃣ Setup environment variables

Create a .env file in the root directory and add the following:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

4️⃣ Run the development server
```bash
npm run dev
```

---

## 👨‍💻 Author

Chetan Malviya


Full Stack Developer | React.js | Node.js | Express.js | MongoDB
