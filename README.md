# 🏫 Nursery Management System

## 📌 Overview
Web-based system to manage a kindergarten with two dashboards: **Admin** & **Teacher**.  
Built using **Angular** (Frontend), **Node.js + Express** (Backend), and **MongoDB Atlas** (Database).

---

## ✨ Features
### Admin Dashboard
- Manage teachers and classes.  
- Add, update, or delete students.  
- Manage subscriptions and salaries.  
- Handle complaints.  

### Teacher Dashboard
- View students in classes.  
- Add monthly and weekly grades.  
- Create quizzes and exams.  
- Simple chat for communication.  

---

## 🛠️ Tech Stack
- **Frontend:** Angular  
- **Backend:** Node.js + Express  
- **Database:** MongoDB Atlas  
- **Other:** JWT Authentication, REST APIs  

---

## 📂 Database Design
- `Users` → teachers & admins.  
- `Students` → name, class, photo, level (KG1, KG2).  
- `Payments` → student_id, amount, month, status.  
- `Complaints` → submitted by users, managed by admin.  
- `Grades` → monthly & weekly grades per student.  

---

## 🚀 Installation & Run
### Backend (Node.js)
```bash
cd backend
npm install
npm start

