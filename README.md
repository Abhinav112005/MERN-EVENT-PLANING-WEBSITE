
# 🎉 MERN Event Planning Website

This is a full-stack **MERN (MongoDB, Express.js, React, Node.js)** based event planning web application designed to help users create, manage, and explore events with ease.

> 🔄 **Note:** This project is still under development and will receive **regular updates and new features**.

---

## ✨ Key Features

- User authentication (Login / Register)
- Create and manage your own events
- Browse upcoming events
- Admin dashboard for event control
- Responsive and intuitive UI
- Secure backend APIs

---

## 🛠 Tech Stack

### Frontend
- React.js
- Axios
- React Router
- Tailwind CSS / CSS Modules

### Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- bcrypt.js for password hashing

---

## 📁 Project Structure

```
MERN-EVENT-PLANING-WEBSITE/
├── client/               # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.js
│       └── index.js
├── server/               # Node.js backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
└── README.md
```

---

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/Abhinav112005/MERN-EVENT-PLANING-WEBSITE.git
cd MERN-EVENT-PLANING-WEBSITE
```

### 2. Install Dependencies

#### Backend
```bash
cd server
npm install
```

#### Frontend
```bash
cd ../client
npm install
```

### 3. Run the Application

#### Backend
```bash
cd ../server
npm start
```

#### Frontend
```bash
cd ../client
npm start
```

---

## 🔐 Environment Variables

Create a `.env` file in the `server/` folder with the following:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## 🧑‍💻 Author

**Abhinav Kumar Yadav**  
📧 abhinavyadav112005@gmail.com  
🌐 [GitHub](https://github.com/Abhinav112005)

---

## 🌟 Support

Give this repository a ⭐️ if you found it helpful!

> 💡 Stay tuned – **more updates and features are on the way**!
