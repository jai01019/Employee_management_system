1️⃣ Overview
The Employee Management System is a web-based application built using the MERN (MongoDB, Express, React, Node.js) stack. It helps organizations manage employees, assign tasks, and monitor progress efficiently.

The system supports two roles:

Admin - Manages employee tasks.

Employee - Views and updates assigned tasks.


2️⃣ Features


2.1 🔹 Admin Dashboard

✅ Create new tasks for employees.

✅ View all assigned tasks.

2.2 🔹 Employee Dashboard

✅ View assigned tasks.

✅ Mark tasks as completed.

2.3 🔹 Authentication System

✅ Login functionality for admin and employees.

✅ User credentials are stored in local storage.


2.4 🔹 Task Management


✅ Track active, completed, and new tasks.

3️⃣ 📂 Project Structure


/employee-management-system

│── /src

│   │── /components

│   │   │── /Auth

│   │   │   └── Login.jsx

│   │   │── /Dashboard

│   │   │   ├── AdminDashboard.jsx

│   │   │   └── EmployeeDashboard.jsx
│   │   │── /other

│   │   │   ├── Header.jsx

│   │   │   ├── CreateTask.jsx

│   │   │   └── AllTask.jsx
│   │── /context

│   │   └── AuthProvider.jsx

│   │── /utils

│   │   └── localStorage.js

│   │── App.jsx

│   │── index.js

│── package.json

│── README.md


4️⃣ 📥 Installation & Setup

4.1 🔹 Clone the Repository

git clone https://github.com/your-repo/employee-management-system.git

cd employee-management-system

4.2 🔹 Install Dependencies

npm install

4.3 🔹 Start the Application

npm run dev

5️⃣ 🔑 Usage


5.1 Admin Login


📧 Email: admin@me.com

🔑 Password: 123

✔️ The admin can create and manage tasks.

5.2 Employee Login

📧 Email: e@e.com (or any other employee email in localStorage.js)

🔑 Password: 123

✔️ Employees can see their assigned tasks.

6️⃣ 🛠️ Technologies Used

6.1 🔹 Frontend

React.js (for UI development)

Tailwind CSS (for styling)

6.2 🔹 Backend (if extended to a full-stack system)

Node.js & Express.js (server-side)

6.3 🔹 Database

LocalStorage (Can be replaced with MongoDB)

6.4 🔹 State Management

React Context API
