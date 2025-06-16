# ⏱️ FixTime – Queue-Free Appointment Booking App

**FixTime** is a smart, real-time appointment scheduling app built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).  
This project is being developed solo by [Rudransh Gupta](https://github.com/Rudrxxx) as part of a 6-week product development sprint.

---

## 🧠 The Problem

Every day, over **99 million Indians** stand in queues for an average of 3 hours — a loss of **297 lakh hours** daily in productivity.  
From hospitals and clinics to local barber shops, people waste hours waiting — even when slots are sometimes free later.

---

## 💡 The FixTime Solution

FixTime allows users to:
- Book appointments online in real time
- See live availability and avoid long queues
- Access services like clinics, salons, and more without wasting time

And service providers can:
- Set their availability
- Reduce downtime
- Manage customer flow efficiently

---

## 🛠️ Tech Stack

| Layer      | Tech                        |
|------------|-----------------------------|
| Frontend   | React, React Router DOM, Axios |
| Backend    | Node.js, Express.js         |
| Database   | MongoDB + Mongoose          |
| Auth       | JWT (JSON Web Tokens), bcryptjs |
| Dev Tools  | VS Code, GitHub, Postman    |

---

## 🔄 Weekly Development Timeline

This project is being built in **6 weeks**:

| Week | Goals Completed ✅ |
|------|--------------------|
| 1    | ✅ MERN setup, user model, auth APIs, frontend routing |
| 2    | 🔄 Login/Register forms, connect frontend to backend |
| 3    | ⏳ Provider dashboard, slot management UI |
| 4    | ⏳ Booking logic, real-time availability |
| 5    | ⏳ Testing, user feedback, bug fixes |
| 6    | ⏳ Launch-ready version, deployment, pitch-ready demo |

---

## 🧪 API Preview

| Method | Route               | Description         |
|--------|---------------------|---------------------|
| POST   | `/auth/register`    | Register new user   |
| POST   | `/auth/login`       | Login existing user |
| GET    | `/`                 | Test server route   |

---

## 🔧 Running Locally

### Backend
```bash
cd server
npm install
touch .env
```

Set up the backend
```bash
cd server
npm install
touch .env
```

Add the following to .env
```
PORT=5001
MONGODB_URI=mongodb://localhost:27017/fixtime
JWT_SECRET=thisissecretkey
```

Start the backend:
```bash
npm run dev
```
Server runs at: http://localhost:5001

Set up the frontend
```bash
cd ../client
npm install
npm start
```
Frontend runs at: http://localhost:3000

🧪 API Endpoints
| Method | Route            | Description         |
| ------ | ---------------- | ------------------- |
| POST   | `/auth/register` | Register new user   |
| POST   | `/auth/login`    | Login existing user |
| GET    | `/`              | Test server route   |

📌 Project Structure
```bash
Fix-Time/
├── client/     # React frontend
├── server/     # Express backend
│   ├── src/
│   │   ├── models/   # Mongoose schemas
│   │   ├── routes/   # API routes
│   │   └── index.js  # Main server file
├── .env
├── README.md
└── .gitignore
```

📍 Maintainer
Built with ❤️ by Rudransh Gupta
→ [GitHub](https://github.com/Rudrxxx)
→ [LinkedIn](https://www.linkedin.com/in/rudransh-gupta-0a2570329/)

