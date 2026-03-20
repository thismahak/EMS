
````markdown
# 👨‍💼 EMS — Employee Management System

A full-stack **Employee Management System** built to manage employee records with secure **admin login** and CRUD operations.  
The project is structured with separate **Frontend** and **Backend** folders for a clean full-stack workflow.

---

## 🚀 Live Demo

**Frontend (Vercel):**  
https://ems-xi-five.vercel.app

**Backend API (Render):**  
https://ems-backend-mx5c.onrender.com

---

## ✨ Features

- Admin login authentication
- Add new employees
- View employee records
- Update employee details
- Delete employee records
- REST API based backend
- Input validation for requests
- MongoDB database integration
- Clean separation of frontend and backend

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs
- express-validator
- Morgan
- CORS

---

## 📁 Project Structure

```bash
EMS/
├── Backend/
│   ├── Middlewares/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── data.js
│   ├── package.json
│   └── server.js
│
├── Frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── tailwind.config.js
│
└── .gitignore
````

---

## 🔐 Backend Routes

### Admin Authentication

* `POST /api/admin/login`

### Employee Management

* `GET /api/employees`
* `POST /api/employees`
* `PUT /api/employees/:id`
* `DELETE /api/employees/:id`

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/thismahak/EMS.git
cd EMS
```

---

## 🖥️ Frontend Setup

```bash
cd Frontend
npm install
npm start
```

The frontend will run on:

```bash
http://localhost:3000
```

---

## 🔧 Backend Setup

```bash
cd Backend
npm install
npm run dev
```

For production:

```bash
npm start
```

---

## 🌱 Environment Variables

Create a `.env` file inside the `Backend` folder and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 👤 Admin Login

Use your admin credentials to log in.

Example:

```json
{
  "username": "admin",
  "password": "admin123"
}
```

---

## 📌 Use Cases

* Manage employee records in one place
* Perform quick CRUD operations
* Practice full-stack MERN development
* Demonstrate authentication + database integration in a college major project

---

## 🔮 Future Improvements

* Role-based access control
* Search and filter employees
* Pagination
* Department-wise employee categorization
* Attendance and leave tracking
* Salary management
* Dashboard analytics
* Profile image upload

---

## 👩‍💻 Author

**Mahak Gupta**
BCA Student | Aspiring MERN Stack Developer

GitHub: [https://github.com/thismahak](https://github.com/thismahak)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub.

```

[1]: https://github.com/thismahak/EMS "GitHub - thismahak/EMS · GitHub"
