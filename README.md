# 📊 Finance Tracking System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Built With](https://img.shields.io/badge/Built%20with-MERN%20Stack-blue)

 #### About
Finance Tracker System is a full-stack web application that helps users track income, expenses, and savings efficiently. It supports user authentication, category-wise tracking, monthly summaries, and detailed transaction management with filtering/search. The application provides a responsive UI with real-time insights using charts and analytics.
---

## 🚀 Features

- 🔐 **User Authentication** — Secure login and signup with JWT  
- 💰 **Track Income & Expenses** — Log and categorize your transactions  
- 🎯 **Set Budget Goals** — Define monthly limits by category  
- 📊 **Real-time Charts** — Visualize data with Pie & Doughnut graphs  
- 🧾 **Filter by Category** — Deep dive into specific spending areas  
- ⏰ **Reminders** — Add upcoming or recurring transactions  
- 📱 **Responsive Design** — Mobile-first UI with Tailwind CSS

---

## 🛠️ Tech Stack

- **MongoDB** — NoSQL database  
- **Express.js** — Backend framework  
- **React.js** — Frontend library  
- **Node.js** — Server runtime  
- **JWT** — Authentication via tokens  
- **Chart.js** — Financial data visualization  
- **Tailwind CSS** — Utility-first responsive styling  

---

## 📦 Installation Guide

### ⚙️ Prerequisites

- Node.js 
- MongoDB or MongoDB Atlas  

---

### 📁 Clone Repository

```bash
git clone https://github.com/your-username/Finance-Tracking-System.git
cd expensync
```

---

### 🔧 Backend Setup

```bash
cd server
npm install
```

Create a `.env` file in `server/` and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

Start the backend server:

```bash
npm start
```

---

### 💻 Frontend Setup

```bash
cd ../frontend
npm client
npm start
```

Open in browser: [http://localhost:3000](http://localhost:3000)

---

## 📊 Live Demo

Check out the live version:  
👉 (https://finance-tracking-system-1.onrender.com)

---

## 📸 Screenshots

### 🖥️ Dashboard Preview

![Finance-Tracking-System Full Demo](./public/demo.png)

### 🌞 Light Mode | 🌙 Dark Mode

| Light Mode                            | Dark Mode                             |
| ------------------------------------ | ------------------------------------- |
| ![Light](./public/light.png)         | ![Dark](./public/dark.png)           |


---

## 📚 Usage Instructions

- **Sign Up / Log In** to access your dashboard  
- **Add Transactions** with categories and amounts  
- **Set Monthly Goals** and track your progress  
- **Visualize with Charts** and analyze your trends  
- **Get Reminders** for important recurring expenses

---

## 📈 Analytics Overview

- 📌 **Category Charts** — See where your money goes  
- 🔄 **Income vs Expenses** — Understand your balance  
- ✅ **Budget Progress** — Stay on track with limits

---

## 🔐 Security Highlights

- 🔒 **JWT Authentication** for protected routes  
- 🔑 **Hashed Passwords** with bcrypt  
- 🚫 **Unauthorized Access Prevention**

---

## 🌟 Upcoming Features
 
- 🔁 Recurring Transactions  
- 💳 Real Time Link With Banks   
- 📉 Advanced Budget Forecasting

---
