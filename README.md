Overview

The Employee Management System is a web-based application built using the MERN (MongoDB, Express, React, Node.js) stack. It helps organizations manage employees, assign tasks, and monitor progress efficiently. The system supports two roles:

Admin - Manages employee tasks.

Employee - Views and updates assigned tasks.

Features

Admin Dashboard:

Create new tasks for employees.

View all assigned tasks.

Employee Dashboard:

View assigned tasks.

Mark tasks as completed.

Authentication System:

Login functionality for admin and employees.

User credentials are stored in local storage.

Task Management:

Track active, completed, and new tasks.

Project Structure

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

Installation & Setup

1. Clone the Repository

git clone https://github.com/your-repo/employee-management-system.git
cd employee-management-system

2. Install Dependencies

npm install

3. Start the Application

npm run dev

Usage

Admin Login

Email: admin@me.com

Password: 123

The admin can create and manage tasks.

Employee Login

Email: e@e.com (or any other employee email in localStorage.js)

Password: 123

Employees can see their assigned tasks.

Technologies Used

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js (if extended to a full-stack system)

Database: LocalStorage (Can be replaced with MongoDB)

State Management: React Context API
