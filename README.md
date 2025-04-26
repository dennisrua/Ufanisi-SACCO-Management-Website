# Ufanisi SACCO Management Website

## 📋 Project Overview
**Ufanisi SACCO Management Website** is a web-based platform designed to help SACCO members apply for loans, save money, withdraw savings, and track their transactions easily and securely. This project was developed as a **Final Year Project** for the **Bachelor of Business Information Technology (BBIT)** program.

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MySQL

---

## 📂 Project Structure
sacco-management/
│
├── backend/
│   ├── server.js
│   ├── db.js
│   ├── routes.js
│   ├── controllers.js
│   ├── middleware.js
│   ├── .env
│   └── package.json
│
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── apply-loan.html
│   ├── transactions.html
│   ├── savings.html
│   ├── landing.html
│   ├── styles.css
│   ├── script.js
│   └── assets/
│
├── database/
│   ├── schema.sql
│   ├── seed.sql
│   └── backup.sql
│
└── README.md

---

## 🔐 Main Features
- User Registration and Login
- Loan Application
- Savings Deposits and Withdrawals
- Transaction Tracking (with date and time records)
- Responsive User Dashboard

---

## ⚙️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd sacco-management

2. Set up the database:
   - Create a MYSQL database
   - Import the SQL scripts from /database/schema.sql and /database/seed.sql

3. Configure the backend:
   - Create a `.env` file in `/backend` with the following content:
    DB_HOST=localhost
    DB_USER=your_mysql_username
    DB_PASSWORD=your_mysql_password
    DB_NAME=your_database_name
    PORT=5000

4. Install backend dependencies:
   - Navigate to the backend folder and install required packages:
    cd backend
    npm install

5. Start the backend server:
   - Run the following command:
    node server.js

6. Open the frontend:
   - Navigate to `/frontend` and open `landing.html` in your browser.

---

## ✨ Future Improvements
- Admin dashboard
- Email notifications
- Password recovery functionality
- Improved security features (like password hashing, JWT authentication)

---

## 👨‍💻 Author
Dennis Rua
