# 📚 MERN E-Learning Platform

A **full-stack E-Learning web application** built using the **MERN stack**, designed to provide a seamless learning experience with secure authentication, course management, payments, and user-friendly UI.

![MERN Stack](https://miro.medium.com/v2/resize:fit:1400/1*2lZq7W1z1T4J0zYtY7KZ9Q.png)

---

## 🚀 Features

✨ User Authentication (JWT-based)  
✨ Secure Password Hashing (bcrypt)  
✨ Role-based Access (Admin / User)  
✨ Course Listing & Enrollment  
✨ File Uploads (Images, Course Content)  
✨ Email Notifications (Nodemailer)  
✨ Payment Integration (Razorpay – Test Mode)  
✨ Responsive UI  
✨ Environment-based Configuration  

---

## 🛠️ Tech Stack

### 🌐 Frontend
- ⚛️ React.js
- 🔀 React Router DOM
- 📡 Axios
- 🔔 React Hot Toast
- 🔐 Google reCAPTCHA
- 🎨 React Icons
- ⚡ Vite

### 🖥️ Backend
- 🟢 Node.js
- 🚂 Express.js
- 🍃 MongoDB + Mongoose
- 🔑 JWT Authentication
- 🔐 bcrypt
- 📤 Multer (File Uploads)
- 📧 Nodemailer
- 💳 Razorpay
- 🆔 UUID

---

## 📁 Project Structure

Mern-Elearning/
│
├── frontend/
│ ├── src/
│ ├── public/
│ └── package.json
│
├── server/
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ ├── utils/
│ ├── index.js
│ └── package.json
│
└── README.md


---

## ⚙️ Environment Variables

Create a `.env` file inside the **server** folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

🧪 Running the Application

Frontend: http://localhost:5173

Backend: http://localhost:5000

🔐 Authentication Flow

🔹 User registers / logs in
🔹 Passwords hashed using bcrypt
🔹 JWT issued & validated via middleware
🔹 Protected routes secured

💳 Payment Flow (Razorpay – Test Mode)

🧾 Course selection
💰 Payment order creation
✅ Payment verification
📦 Enrollment confirmation
