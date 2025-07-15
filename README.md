
# 🔐 Secure User Authentication System – PRODIGY_FS_01

This project is a full-stack secure user authentication system built using **Node.js**, **Express**, **MongoDB**, and vanilla **HTML/CSS/JS**. It supports:

- 🔐 User Registration (Signup)
- 🔑 User Login with password verification
- 📄 Profile page access with authentication check
- 🚪 Logout functionality with token invalidation

---


<img width="600px" height="968" alt="image" src="https://github.com/user-attachments/assets/27a6cfce-f609-498c-8d08-b0e888fa2499" />      <img width="600px" height="962" alt="image" src="https://github.com/user-attachments/assets/725ebf52-5065-42f6-869f-94681797192a" />
             
<img width="1917" height="916" alt="image" src="https://github.com/user-attachments/assets/efd4fd24-74a4-4065-b68a-812809d83c11" />


---

## 📁 Project Structure

```
Prodigy_FS_01/
├── middleware/
│   └── authMiddleware.js        # Middleware to protect private routes
├── models/
│   └── User.js                  # Mongoose schema for user data
├── public/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── profile.html
│   └── script.js                # Logout logic and token check
├── routes/
│   └── auth.js                  # Handles signup and login routes
├── .env                         # Environment variables
├── server.js                    # Express server configuration
├── package.json                 # Project dependencies
```

---

## ⚙️ Features

- ✅ User signup with secure password hashing (bcrypt)
- ✅ User login with JWT token generation
- ✅ Token-based authentication for protected routes
- ✅ Profile page access only if logged in
- ✅ Logout functionality using `localStorage`
- ✅ Clean and responsive frontend

---

## 💻 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Security**: bcryptjs for password hashing, jsonwebtoken for authentication
- **Tools**: VS Code, Git, GitHub, Postman

---

## 🚀 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/VinayLR15/PRODIGY_FS_01.git
cd PRODIGY_FS_01
```

2. **Install dependencies**
```bash
npm install
```

3. **Create a `.env` file**
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

4. **Start the server**
```bash
node server.js
```

5. **Open in browser**
```
http://localhost:5000/signup.html
```

---

## 🧪 Testing

- Register via `signup.html`
- Login via `login.html`
- After login, redirected to `profile.html`
- Token stored in `localStorage`
- Logout clears token and redirects back to login

---


## 📄 License

This project is licensed under the **MIT License**.

---

## 🙋‍♂️ Author

**Vinay L R**  
GitHub: [VinayLR15](https://github.com/VinayLR15)
