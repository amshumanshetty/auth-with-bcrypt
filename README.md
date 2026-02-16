# 🔐 Auth With Bcrypt

A secure authentication system built using Node.js that implements user registration and login with password hashing using bcrypt.

---

## 🚀 Features

- User Registration
- User Login Authentication
- Password hashing using bcrypt
- Secure password storage
- Environment variables support (.env)
- Clean project structure

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- bcrypt
- dotenv
- JavaScript

---

## 📁 Project Structure
```bash
auth-with-bcrypt/
│
├── public/          # Static files (CSS, images, client JS)
│   └── css/
│
├── views/           # EJS templates
│   ├── partials/
│   ├── home.ejs
│   ├── login.ejs
│   ├── register.ejs
│   └── secrets.ejs
│
├── index.js         # Main server file
├── package.json
├── .env.example
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/amshumanshetty/auth-with-bcrypt.git
```

Navigate into project:


```
cd auth-with-bcrypt
```

Install dependencies:

```

npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory:



Session

```
SESSION_SECRET=your_session_secret
```

PostgreSQL Database

```
PG_USER=your_database_user
PG_HOST=localhost
PG_DATABASE=your_database_name
PG_PASSWORD=your_database_password
PG_PORT=5432
```

---

## ▶️ Run the Application


```
npm start
```

or


```
node index.js
```

---

## 🔒 Security

Passwords are hashed using bcrypt before storing to ensure secure authentication practices.

---

## 📌 Future Improvements

- JWT authentication
- Database integration
- Session management
- Input validation
- Password reset functionality

---

## 👨‍💻 Author

Amshuman Shetty

GitHub: https://github.com/amshumanshetty
