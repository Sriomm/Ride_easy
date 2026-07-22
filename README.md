# Ride_easy

# 🚖 Uber Clone

A full-stack Uber Clone web application built using the **MERN Stack** that allows users to book rides, view nearby captains, and experience real-time ride updates.

---

## 📌 Overview

This project replicates the core functionalities of Uber, including user authentication, ride booking, captain management, and real-time communication between riders and drivers.

The application is divided into two parts:

- **Frontend:** React + Vite
- **Backend:** Node.js + Express + MongoDB
- **Real-Time Communication:** Socket.IO

---

## 🚀 Features

### 👤 User Module

- User Registration
- User Login & Authentication
- JWT Authentication
- Book a Ride
- Live Ride Status
- Ride History

### 🚗 Captain Module

- Captain Registration
- Captain Login
- Accept/Reject Ride Requests
- Update Ride Status
- Live Location Updates

### 🌍 Maps & Location

- Search Pickup Location
- Search Destination
- Calculate Route
- Estimate Fare
- Distance Calculation

### ⚡ Real-Time Features

- Live Ride Requests
- Live Captain Updates
- Socket.IO Integration
- Ride Status Notifications

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- React Router
- Axios
- CSS

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt
- Socket.IO

## Database

- MongoDB Atlas / Local MongoDB

---

# 📂 Project Structure

```
Uber-Clone
│
├── Backend
│   ├── controllers
│   ├── db
│   ├── middlewares
│   ├── models
│   ├── routes
│   ├── services
│   ├── app.js
│   ├── server.js
│   ├── socket.js
│   └── package.json
│
├── Frontend
│   ├── public
│   ├── src
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/uber-clone.git

cd uber-clone
```

---

## 2️⃣ Backend Setup

```bash
cd Backend

npm install
```

Create a `.env` file

```env
PORT=4000

MONGO_URI=Your MongoDB URI

JWT_SECRET=Your Secret Key
```

Start Backend

```bash
npm start
```

or

```bash
npm run dev
```

---

## 3️⃣ Frontend Setup

```bash
cd Frontend

npm install

npm run dev
```

Frontend will start at

```
http://localhost:5173
```

---

# 🔗 API Endpoints

## User

| Method | Endpoint |
|----------|----------------|
| POST | /users/register |
| POST | /users/login |
| GET | /users/profile |

---

## Captain

| Method | Endpoint |
|----------|------------------|
| POST | /captains/register |
| POST | /captains/login |
| GET | /captains/profile |

---

## Ride

| Method | Endpoint |
|----------|----------------|
| POST | /rides/create |
| GET | /rides/fare |
| POST | /rides/confirm |

---

# 📸 Screenshots

Add screenshots here.

```
Home Page

Login Page

Signup Page

Booking Screen

Captain Dashboard

Ride Tracking
```

---

# 🔐 Authentication

- JWT Authentication
- Password Hashing using bcrypt
- Protected Routes
- Authorization Middleware

---

# 📡 Real-Time Communication

Socket.IO is used for:

- Ride Request Notifications
- Live Driver Location
- Ride Acceptance
- Ride Completion
- Status Updates

---

# 💻 Running the Project

Open two terminals.

### Backend

```bash
cd Backend

npm install

npm start
```

### Frontend

```bash
cd Frontend

npm install

npm run dev
```

---

# 📦 Dependencies

## Backend

- Express
- Mongoose
- JWT
- bcrypt
- dotenv
- Socket.IO

## Frontend

- React
- Axios
- React Router
- Vite

---

# 🎯 Future Improvements

- Google Maps API Integration
- Online Payments
- Ride Scheduling
- Driver Ratings
- User Reviews
- Push Notifications
- Admin Dashboard
- Dark Mode
- Ride Cancellation
- OTP Verification

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Create a Pull Request

---

# 📝 License

This project is developed for educational and learning purposes.

---

# 👨‍💻 Author

**Sriom Bakshi**

- GitHub: https://github.com/Sriomm
- LinkedIn: 

---

⭐ If you found this project helpful, please give it a star!
