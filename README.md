# 🎬 BookMyShow Clone

A full-stack MERN web application that replicates the core features of BookMyShow, including movie listings, booking, and user authentication.

## 📚 Project Overview

**Name:** BookMyShow Clone  
**Author:** Param Dodal  

---

## 🧰 Tech Stack

### 🖥️ Frontend
- React
- JavaScript
- HTML
- CSS

### ⚙️ Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### 🔧 Other Tools
- Axios
- dotenv
- nodemon
- concurrently (optional)

---

## 📁 Project Structure

bookmyshow-clone/
├── README.md
├── back-end/
│ ├── dbConnection.js
│ ├── routes.js
│ ├── schema.js
│ ├── server.js
│ ├── package.json
│ └── package-lock.json
└── front-end/
├── public/
├── src/
├── package.json
├── package-lock.json
└── .gitignore

yaml
Copy
Edit

---

## 🚀 Features

- ✅ Browse movies, showtimes, and venues  
- ✅ Book tickets for available shows  
- ✅ User authentication (sign up / log in)  
- ✅ RESTful backend API with MongoDB  
- ✅ Responsive UI built with React  

---

## ⚙️ Setup Instructions

### 📌 Prerequisites
- Node.js
- MongoDB
- npm or yarn

---

### 📥 Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/Paramdodal/Book-My-Show-Clone.git
cd Book-My-Show-Clone
```
2. Setup Backend
```bash
cd back-end
npm install
```
Create a .env file in back-end/:
```bash
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```
Run the backend server:
```bash
npm start
```
3. Setup Frontend
```bash
cd ../front-end
npm install
npm start
```
🌐 Running the App
Frontend: http://localhost:3000

Backend: http://localhost:5000

🔗 API Endpoints
Method	Route	Description
GET	  /movies	Get all movies
POST	/book	Book a show
POST	/register	User registration
POST	/login	User login

Base URL: http://localhost:5000

🔐 Environment Variables
Create a .env file in back-end/:
```bash
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```
#### 🖼️ Screenshots

![Screenshot 2025-06-07 220649](https://github.com/user-attachments/assets/533e8ebb-ecca-48b6-8277-fa1fd73f6c83)
![Screenshot 2025-06-07 220707](https://github.com/user-attachments/assets/478e6c2a-8969-4c72-94b3-e1f42c2bb7ae)
![Screenshot 2025-06-07 220804](https://github.com/user-attachments/assets/f312f837-c799-4518-868d-0d2d25abc8db)


