# Project 3 - Database Integration

## 📌 Project Overview

This project is developed as **Project 3** of the **DecodeLabs Full Stack Development Industrial Training Kit 2026**.

The objective of this project is to connect the backend with a MongoDB database and perform CRUD (Create, Read, Update, Delete) operations using Node.js, Express.js, and Mongoose.

---

## 🚀 Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- CORS
- Nodemon

---

## 📁 Project Structure

```
Project3-DatabaseIntegration/
│
├── config/
│   └── db.js
│
├── controllers/
│   └── userController.js
│
├── models/
│   └── User.js
│
├── routes/
│   └── users.js
│
├── server.js
├── package.json
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone <repository-link>
```

Go to project directory

```bash
cd Project3-DatabaseIntegration
```

Install dependencies

```bash
npm install
```

Run the project

```bash
npm run dev
```

---

## 🌐 Server

```
http://localhost:5000
```

---

## 🗄 Database

```
MongoDB
Database Name: project3DB
```

---

## 📡 API Endpoints

### Create User

```
POST /api/users
```

### Get All Users

```
GET /api/users
```

### Get Single User

```
GET /api/users/:id
```

### Update User

```
PUT /api/users/:id
```

### Delete User

```
DELETE /api/users/:id
```

---

## 🧪 Sample JSON

```json
{
  "name": "Adeel Sattar",
  "email": "adeel@gmail.com",
  "age": 21
}
```

---

## ✅ Features

- MongoDB Database Integration
- Express REST API
- CRUD Operations
- Mongoose Schema
- Error Handling
- JSON Response
- Clean Project Structure

---

## 👨‍💻 Author

**Adeel Sattar**

BS Software Engineering

The University of Lahore

---

## 📄 License

This project is created for educational purposes as part of the DecodeLabs Full Stack Development Industrial Training Program.
