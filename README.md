# 🔐 Auth With Bcrypt

A secure authentication system built with Node.js, Express, PostgreSQL, Passport.js, and bcrypt.  
This project demonstrates best practices for user authentication including password hashing, session handling, and protected routes.

---

## 🚀 Features

✅ User Registration with password hashing (bcrypt)  
✅ Secure Login Authentication (Passport Local Strategy)  
✅ Session-based authentication  
✅ Protected routes using middleware  
✅ PostgreSQL database integration  
✅ Environment variable configuration  
✅ EJS templating

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- PostgreSQL (pg)
- Passport.js
- bcrypt
- express-session
- dotenv
- EJS

---

## 📦 Installation

Clone the repository:

git clone https://github.com/amshumanshetty/auth-with-bcrypt.git


Navigate into project:

cd auth-with-bcrypt


Install dependencies:

npm install
---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

Example:

Session

SESSION_SECRET=your_session_secret

PostgreSQL Database

PG_USER=your_database_user
PG_HOST=localhost
PG_DATABASE=your_database_name
PG_PASSWORD=your_database_password
PG_PORT=5432

⚠️ Never commit your `.env` file.

---

## 🗄️ Database Setup

Make sure PostgreSQL is installed and running.

Create a database and table:

Example:

