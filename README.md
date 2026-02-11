# Frontend Developer Internship Assignment

A full‑stack web application built as per the assignment requirements for the **Frontend Developer Intern** role.  
This project includes a **React frontend** and a **Node.js/Express backend** with JWT authentication and CRUD operations.

---

## 🧠 Features

✅ User authentication (Signup & Login with JWT)  
✅ Protected dashboard  
✅ Display user profile (from backend)  
✅ CRUD operations on Tasks (create, read, delete)  
✅ Responsive UI with TailwindCSS  
✅ Secure password hashing with bcrypt  
✅ Modular and scalable codebase

---

## 📁 Project Structure

Frontend-Developer-Task/
├── backend/
│ ├── config/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── .env
│ └── server.js
├── frontend/
│ ├── src/
│ ├── public/
│ └── package.json
├── README.md
└── .gitignore

---

## 🛠️ Tech Stack

- **Frontend:** React.js, TailwindCSS, Axios, React Router  
- **Backend:** Node.js, Express.js, MongoDB (local), JWT, bcrypt  
- **Database:** MongoDB local instance  
- **Tools:** Postman (for API testing)

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/adarshinibandla/Frontend-Developer-Task.git
cd Frontend-Developer-Task
```

## 2. Start Backend
cd backend
npm install


Create a .env file in backend folder and add:

MONGO_URI=mongodb://127.0.0.1:27017/assignmentDB
JWT_SECRET=mysecret123
PORT=5000


Then run:

npx nodemon server.js


You should see:

MongoDB Connected
Server running on port 5000

## 3. Start Frontend

Open a new terminal:

cd frontend
npm install
npm start


Opens on: http://localhost:3000

## 📌 Usage

Register a new user

Login with registered email & password

Access Dashboard

Add, view, and delete tasks

## 🔍 API Endpoints

Feature	Endpoint	Method
Signup	/api/auth/register	POST
Login	/api/auth/login	POST
Profile	/api/profile	GET
Tasks	/api/tasks	GET/POST/DELETE
## 🧾 Additional Notes

You can test APIs using Postman

JWT tokens are stored in localStorage

Backend uses bcrypt for password hashing

## 🏆 Assessment Criteria Covered

✔ Functioning authentication with JWT
✔ Protected frontend routes
✔ CRUD operations with backend API
✔ Password security and validation
✔ Responsive UI with TailwindCSS
✔ Clean and modular project structure

## 📎 Contact

For any questions, reach out:

Adarshini Bandla


